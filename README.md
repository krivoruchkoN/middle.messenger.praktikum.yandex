## Описание

 Разработка своего чата с целью углубить имеющиеся и получить новые знания.  
 Реализация чата от его прототипа на бумаге до развёртывания на Heroku.  
 Для вдохновения использовались Telegram, Yandex.Messenger и WhatsApp.

## Команды

- `npm run parcel-dev` — чистка текущего билда, сборка и запуск версии для разработчиков
- `npm run parcel-build` — чистка текущего билда и сборка стабильной версии,
- `npm run start` — чистка текущего билда, сборка и запуск Express сервера

## Примеры использования

На корневой странице организован роутинг по реализованным страницам:
- /login - страница входа, есть переход на страницу регистрации,
- /signup - страница регистрации, есть переход на страницу входа,
- /chat - страница с основным функционалом чата, пока заглушка,
- /profile - страница с информацией о пользователе, есть переход на страницу чата,
- /404 - страница ошибки 404, есть переход на главную страницу,
- /500 - страница ошибки 500, есть переход на главную и на страницу issues репозитория.


## Полезные ссылки
- Макеты и прототипы: https://www.figma.com/file/SKgS69xThGR7KqhBW1vsfk/?node-id=2%3A7935
- Развернутый проект: https://musing-cray-f98793.netlify.app  
- PR sprint_1: https://github.com/Praktikum-krivoruchkoND/middle.messenger.praktikum.yandex/pull/1
