# n3tdom_microservices
n3tdom microservices repository

- [n3tdom_microservices](#n3tdom_microservices)
  - [hw-1x шаблон](#hw-1x-шаблон)
    - [Основное задание](#Основное-задание)
    - [Задание со *](#Задание-со-)
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

### Задание со *


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
