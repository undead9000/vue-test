Для запуска проекта локально достаточно скачать файлы в одну папку и открыть index.html в браузере. Также можно посмотреть по адресу http://q28test.net.ua/vuejs/

#### Описание задачи и статус выполнения  
1. _Отобразить данные в виде таблицы_ - сделано.  
2. _Реализовать живой поиск по данным таблицы_ - сделано.  
3. _Вывести поле “Итого” - сумма по всем элементам поля “Стоимость”_ - сделано.  
4. _Реализовать сортировку данных по полям “Название”, “Локация”_ - сделано.   
5. _Реализовать живое редактирование данных в каждой строке таблицы (реализовать валидацию полей, исключить невалидные данные)_ - сделано частично, проверяется только поле с ценой на соответствие числовому формату.  
6. _Реализовать страницу детального просмотра выбранного элемента таблицы_ - сделано. Переход реализован по клику на порядковый номер.  
7. _Реализовать хранение данных в MongoDB (или любой другой, например Firebase и т.д.), реализовать простой  CRUD для работы с данными._ - сделано отчасти. Данные подгружаются из Firebase, но не реализованы операции над данными.  

#### Доработки  
Если бы это был реальный проект, то я бы, в первую очередь, доработал недостающую функциональность. Далее (возможно, параллельно с предыдущим) я переработал бы структуру таким образом, чтобы за вывод общей таблицы и вывод детальной информации отвечали отдельные шаблоны. Также мне понадобилось бы изменить проект, чтобы он запускался в виде веб-приложения с подключением нужных библиотек автоматически, а не в виде html-страницы.

#### Ответы на вопросы тестового задания  
1. Я думаю, что более опытному разработчику потребовалось бы порядка 4-6 часов на выполнение такой работы.  
2. Я затратил на работу около трёх дней. Это связано с тем, что с большей частью возникающих вопросов я ранее не сталкивался и попутно много времени тратил на изучение руководств и примеров решений.  
3. Использовал Bootstrap, чтобы не тратить лишнее время на вёрстку; firebase.js и vuefire для подключения к базе Firebase и удобной работы с полученными данными соответственно (+использовал бы эту связку для CRUD).  
4. К сожалению, аналогичных задач пока не выполнял.  
5. Активно обращался к документации по Vue, изучал отдельные чужие решения, чтобы понять, как правильно подходить к выполнению и пользовался StackOverflow, если возникали затруднения, которые не получалось решить самому. К людям не обращался за неимением таких знакомых.  
6. Теперь на аналогичное задание я затратил бы меньше времени. Думаю, уложился бы в 10-12 часов.
