В состав входит контейнер webdav-client, который монтирует Яндекс-диск для создания бэкапов. Для запуска контейнера нужно указать пароль для приложения Яндекс-Диск в файле .env или в командной строке при ручном запуске:

~~~
WEBDRIVE_PASSWORD=<пароль для приложения яндексдиска> docker-compose up -d
~~~

Узнать, как создать пароль для приложения можно по этой ссылке: https://yandex.ru/support/id/authorization/app-passwords.html
