# n3tdom_microservices
n3tdom microservices repository

- [n3tdom_microservices](#n3tdom_microservices)
  - [hw-1x шаблон](#hw-1x-шаблон)
    - [Основное задание](#Основное-задание)
    - [Задание со * #1: Запустить с пробросом переменных-алиасов](#Задание-со--1-Запустить-с-пробросом-переменных-алиасов)
    - [Задание со * #2: Пересобрать облегченные образы на базе alphine linux](#Задание-со--2-Пересобрать-облегченные-образы-на-базе-alphine-linux)
  - [hw-11 шаблон](#hw-11-шаблон)
    - [Основное задание](#Основное-задание-1)
    - [Задание со *: поднятие инстансов (gcp+terraform+ansible+packer)](#Задание-со--поднятие-инстансов-gcpterraformansiblepacker)
  - [hw-10 docker-2](#hw-10-docker-2)
    - [Основное задание](#Основное-задание-2)
    - [Задание со * -](#Задание-со---)
    - [Задание со ** -](#Задание-со---)
  - [hw-09 docker-1](#hw-09-docker-1)
    - [Основное задание](#Основное-задание-3)
    - [Задание со * -](#Задание-со----1)

---
## hw-1x шаблон
### Основное задание

### Задание со * #1: Запустить с пробросом переменных-алиасов
docker run -d --network=reddit --network-alias=db  -v reddit_db:/data/db mongo:latest
docker run -d --network=reddit --network-alias=reddit-post  -e "POST_DATABASE_HOST=db" n3tdom/post:1.0
docker run -d --network=reddit --network-alias=reddit-comment  -e "COMMENT_DATABASE_HOST=db" n3tdom/comment:1.0
docker run -d --network=reddit -p 9292:9292 \
-e "POST_SERVICE_HOST=reddit-post" \
-e "COMMENT_SERVICE_HOST=reddit-comment" \
n3tdom/ui:2.0

### Задание со * #2: Пересобрать облегченные образы на базе alphine linux
Не выполнялось


docker run -d --network=reddit --network-alias=post_db --network-alias=comment_db mongo:latest
docker run -d --network=reddit --network-alias=post n3tdom/post:1.0
docker run -d --network=reddit --network-alias=comment n3tdom/comment:1.0
docker run -d --network=reddit -p 9292:9292 n3tdom/ui:2.0

---
## hw-11 шаблон
### Основное задание
- Создан docker-host на gcp
- Создан image/Dockerfile
- Image загружен на docker hub

### Задание со *: поднятие инстансов (gcp+terraform+ansible+packer)
Не выполнялось

## hw-10 docker-2
### Основное задание
docker run --pid host #Запускает контейнер в неймспейсе docker host - из контейнера становятся видны процессы хоста.


### Задание со * -

### Задание со ** -

## hw-09 docker-1
### Основное задание
Установлен докер, знакомство с основными командами

### Задание со * -
>На основе вывода команд объясните чем отличается контейнер от образа

1. Единственная одинаковая для образа и контейнера секция в выводе docker inspect - содержит информацию о хосте и среде где создан image/container: hostname, attachStd, env, cmd, parent image.
2. Образ представляет из себя набор слоев, вывод команды указывает их список, название образа в репозитории, образ на основе которого он создавался
3. Контейнер являет собой уже готовый к запуску объект с сетевыми интерфейсами, маунтами и другими свойствами относительно docker daemon
