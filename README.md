# warehouse

a [Sails v1](https://sailsjs.com) application


### Links

+ [Sails framework documentation](https://sailsjs.com/get-started)


### Install

+ Требуется версия Node.js 10+ и MongooDB v3+
+ Скачивание репозитория `git clone https://github.com/Damassk/warehouse ./<folder name>`
+ Установка пакетов внутри директории проекта `npm install`
+ Запуск проекта `node app.js` (проект работает на порту: 1503)

WARNING: API избавлено от чрезмерных проверок на формат данных, сохранность приходящих данных и тд... Потому что
предполагает обработку и формализацию данных на клиентской стороне. Также вывод ошибок можно кастомизировать, но в данном
случае такое задачи не стояло. Проект запускается в режиме `develop`.

В папке `api` находится основной код проекта API. Все методы вынесены в `controllers` и распределены по попкам,
а также разбиты в файлы `Action2` формата с поддержкой `Waterline`.

