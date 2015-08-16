#Тестовое задание №1 в ШРИ Яндекса 2015 "Табло аэропорта"

Демо http://buzzinoffbond.github.io/shri-aero/

В качестве вдохновения было использовано табло http://basel.aero/

####Выпадающеие подробности
Реализованы с помощью ```<details><summary>```, он нативно поддерживается во всех webkit браузерах. Для Firefox и IE/Edge 
был использован полифил http://www.smashingmagazine.com/2014/11/complete-polyfill-html5-details-element/ В остальном только HTML/CSS.

####Подсветка столбцов
Очень высокий абсолютно спозиционированный псевдоэлемент обрезающийся высотой таблицы
https://github.com/Buzzinoffbond/shri-aero/blob/master/css/styles.css#L112-L121

####Таблица-зебра
На фон устанавливаем repeating-linear-gradient с высотой строки
https://github.com/Buzzinoffbond/shri-aero/blob/master/css/styles.css#L65-L74

####Модальные окна
Ссылки и псевдокласс :target
https://github.com/Buzzinoffbond/shri-aero/blob/master/css/styles.css#L300-L342
