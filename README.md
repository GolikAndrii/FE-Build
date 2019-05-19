# Front-End test. Calendar
### Для реализации использовал следующие технологии:
* jQuery и JavaScript + Html + Scss
* Css стили писал через препроцессор Sass (файл ./src/style.scss)
* Согласно задания использовал сборщик Webpack с самыми необходимыми модулями и плагинами для сборки файлов html, scss+css, js+jquery
* Для работы в режиме разработки необходимо выполнить команду "npm run start" и работать в папке /src.
* Для production необходимо выполнить команду "npm run build". После этого для просмотра сайта в браузере необходимо запустить файл /dist/index.html

### Из функций, указанных в задании, реализованы следующие:
* возможность перехода по месяцам
* при клике на любую дату текущего месяца есть возможность записи события в LocalStorage.
* при повторном клике на данной дате есть возможность редактирования события
* при нажатии на кнопке "Сегодня" осуществляется переход на текущий месяц
* при нажатии на кнопку "Очистить" осуществляется удаление всех событий из LocalStorage
* текущая дата "подсвечена"
* выходные дни (субботы и воскресенья) подсвечены

## Посмотреть на GitHub page:
https://golikandrii.github.io/
