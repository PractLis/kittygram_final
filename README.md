![workflow](https://github.com/PractLis/kittygram_final/actions/workflows/main.yml/badge.svg)

Социальная сеть любителей котов Kittygram

Проект развернут на сайте: https://catgram.ddns.net/

Описание
Сайт для любителей котов с личным кабинетом, возможностью публикации фотографий котов и присваивания им достижений.

Технологии
Python 3.9, Django 3.2.3, Django REST framework

Запуск проекта в dev-режиме
Клонируйте репозиторий и перейдите в него в командной строке:

<b>git clone https://github.com/l1sser/kittygram_final.git
cd kittygram_final</b>

Запустите проект с помощью команды:

<b>docker compose up</b>

Соберите статику Django командой:

<b>docker compose exec backend python manage.py collectstatic</b>

Скопируйте статику командой:

<b>docker compose exec backend cp -r /app/collected_static/. /static/static/</b>
Сайт будет доступен по адресу http://127.0.0.1:9000/ .

Создатель Лис <a href='https://github.com/PractLis'>Github</a>