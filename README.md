# Домашнее задание к лекции «Docker Compose»

Реализован работа сервера из домашего задания `CRUD: Склады и запасы` с помощь котейниизации с использованием:

* Nginx 
* PostgreSQL запускается до Django.
* Django запускается через Gunicorn

![контейниеры Docker](/img/pic1.png)

* [Docerfile](/stocks_products/Dockerfile) для `django` в директории stocks_products
* [Docerfile](/nginx/Dockerfile) для `nginx` в директории nginx
* [Конфигурация](/nginx/nginx.conf) для `nginx` в директории nginx
* Права доступа для базы данных следует указать в файле переменнйо окружения [.env.dev](/.env.dev)
* [Docer-compose файл](\docker-compose.yml) в корне проекта



