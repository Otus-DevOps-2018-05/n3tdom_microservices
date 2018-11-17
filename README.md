# n3tdom_microservices
n3tdom microservices repository

- [n3tdom_microservices](#n3tdom_microservices)
  - [hw-1x](#hw-1x)
    - [Основное задание](#Основное-задание)
    - [Задание со * -](#Задание-со---)
  - [hw-19 kubernetes-3](#hw-19-kubernetes-3)
    - [Основное задание](#Основное-задание-1)
  - [hw-18 kubernetes-2](#hw-18-kubernetes-2)
    - [Основное задание](#Основное-задание-2)
    - [Задание со * -](#Задание-со----1)
  - [hw-17 kubernetes-1](#hw-17-kubernetes-1)
    - [Основное задание](#Основное-задание-3)
    - [Задание со * - описать kubernetes the hard way в виде Ansible-плейбуков](#Задание-со----описать-kubernetes-the-hard-way-в-виде-ansible-плейбуков)
  - [hw-16 logging-1](#hw-16-logging-1)
    - [Основное задание](#Основное-задание-4)
    - [Задание со * - С нашим приложением происходит что-то странное. Траблшут кода из https://github.com/Artemmkin/bugged-code](#Задание-со----С-нашим-приложением-происходит-что-то-странное-Траблшут-кода-из-httpsgithubcomartemmkinbugged-code)
  - [hw-15 monitoring-2](#hw-15-monitoring-2)
    - [Основное задание](#Основное-задание-5)
    - [Задание со * -](#Задание-со----2)
  - [hw-14 monitoring-1](#hw-14-monitoring-1)
    - [Основное задание](#Основное-задание-6)
    - [Задание со * #1 - Добавьте в Prometheus мониторинг MongoDB с использованием экспортера (не рекомендуется dcu/mongodb_exporter)](#Задание-со--1---Добавьте-в-prometheus-мониторинг-mongodb-с-использованием-экспортера-не-рекомендуется-dcumongodb_exporter)
    - [Задание со * #2 - Добавьте в Prometheus мониторинг сервисов comment, post, ui с помощью blackbox экспортера.](#Задание-со--2---Добавьте-в-prometheus-мониторинг-сервисов-comment-post-ui-с-помощью-blackbox-экспортера)
    - [Задание со * #3 - Напишите Makefile который билдит docker images + пушит их в docker hub](#Задание-со--3---Напишите-makefile-который-билдит-docker-images--пушит-их-в-docker-hub)
  - [hw-13 gitlab-ci-1](#hw-13-gitlab-ci-1)
    - [Основное задание](#Основное-задание-7)
    - [Задание со * #1 - Продумайте автоматизацию развертывания и регистрации Gitlab CI Runner.](#Задание-со--1---Продумайте-автоматизацию-развертывания-и-регистрации-gitlab-ci-runner)
    - [Задание со * #2 - Настройте интеграцию вашего Pipeline с тестовым Slack-чатом,](#Задание-со--2---Настройте-интеграцию-вашего-pipeline-с-тестовым-slack-чатом)
  - [hw-12 docker-4](#hw-12-docker-4)
    - [Основное задание](#Основное-задание-8)
    - [Задание со * - docker-compose.override.yml Дебаг и редактирование соурс кода без ребилда образа](#Задание-со----docker-composeoverrideyml-Дебаг-и-редактирование-соурс-кода-без-ребилда-образа)
  - [hw-11 docker-3](#hw-11-docker-3)
    - [Основное задание](#Основное-задание-9)
    - [Задание со * #1: Запустить с пробросом переменных-алиасов](#Задание-со--1-Запустить-с-пробросом-переменных-алиасов)
    - [Задание со * #2: Пересобрать облегченные образы на базе alphine linux](#Задание-со--2-Пересобрать-облегченные-образы-на-базе-alphine-linux)
  - [hw-10 docker-2](#hw-10-docker-2)
    - [Основное задание #Запускает контейнер в неймспейсе docker host - из контейнера становятся видны процессы хоста.](#Основное-задание-Запускает-контейнер-в-неймспейсе-docker-host---из-контейнера-становятся-видны-процессы-хоста)
    - [Задание со * - Docker + Terraform + Ansible + Packer](#Задание-со----docker--terraform--ansible--packer)
  - [hw-09 docker-1](#hw-09-docker-1)
    - [Основное задание](#Основное-задание-10)
    - [Задание со * - На основе вывода команд объясните чем отличается контейнер от образа](#Задание-со----На-основе-вывода-команд-объясните-чем-отличается-контейнер-от-образа)

---
## hw-1x
### Основное задание
### Задание со * -



---
## hw-19 kubernetes-3
### Основное задание
- Знакомство с конфигурацией сети
  - Nodeport
  - LoadBalancer
  - Ingress
  - TLS Termination
  - Network Policy
  - Secrets

- Знакомство с конфигурацией хранилища
  - Volume = gce disk + mount
  - Persistent Volume = хранилище как ресурс
  - PersistentVolumeClaim = запрос на выделение хранилища
  - Dynamic Volume Allocation = запросы на выделения создаются в автоматическом режиме


---
## hw-18 kubernetes-2
### Основное задание
- Написание конфигураций для приложения (.yml)
- Развертывание в minicube
- Развертывание в GKE
- Namespaces

### Задание со * -
TODO: Не выполнялось

---
## hw-17 kubernetes-1
### Основное задание
- Папка конфигураций kubernetes/
- Пройден туториал kubernetes the hard way

### Задание со * - описать kubernetes the hard way в виде Ansible-плейбуков
TODO: Не выполнялось


---
## hw-16 logging-1
### Основное задание
- Приложение + EFK
- Структурированные локи (post)
- Неструктурированные логи (ui)
- Пример трейсинга в zipkin

### Задание со * - С нашим приложением происходит что-то странное. Траблшут кода из https://github.com/Artemmkin/bugged-code
TODO: Не выполнялось


---

## hw-15 monitoring-2
### Основное задание
Мониторинг Docker контейнеров (cAdvisor)
Визуализация метрик (Grafana)
Сбор метрик работы приложения и бизнес метрик
Настройка и проверка алертинга (Alertmanager, slack)

### Задание со * -
TODO: Не выполнялось


## hw-14 monitoring-1
### Основное задание
Prometheus - установка и знакомство
Мониторинг и экспортеры

https://hub.docker.com/r/n3tdom
docker-machine ip docker-host

### Задание со * #1 - Добавьте в Prometheus мониторинг MongoDB с использованием экспортера (не рекомендуется dcu/mongodb_exporter)
TODO: Не выполнялось

### Задание со * #2 - Добавьте в Prometheus мониторинг сервисов comment, post, ui с помощью blackbox экспортера.
TODO: Не выполнялось

### Задание со * #3 -  Напишите Makefile который билдит docker images + пушит их в docker hub
TODO: Не выполнялось

## hw-13 gitlab-ci-1
### Основное задание
- Развертывание gitlab-ci
- Runner и тестовый пайплайн

### Задание со * #1 - Продумайте автоматизацию развертывания и регистрации Gitlab CI Runner.
TODO: Не выполнялось

### Задание со * #2 - Настройте интеграцию вашего Pipeline с тестовым Slack-чатом,
который вы использовали ранее.
TODO: Не выполнялось

## hw-12 docker-4
### Основное задание
- Работа с сетями в Docker
- Использование docker-compose

### Задание со * - docker-compose.override.yml Дебаг и редактирование соурс кода без ребилда образа
- Параметры запуска передаются с помощьюh ttps://docs.docker.com/v17.09/compose/compose-file/#entrypoint При этом CMD[] внутри Dockerfile игнорируется.
- При запуске команды из второго -f дополняют/перезаписывают команды в первом
```docker-compose -f docker-compose.yml -f docker-compose-override.yml up -d```
- Логи пумы направленные в stdout sterror можно увидеть с помощью ```docker logs reddit_ui_1```

## hw-11 docker-3
### Основное задание
- Создан docker-host на gcp
- Создан image/Dockerfile
- Image загружен на docker hub

### Задание со * #1: Запустить с пробросом переменных-алиасов
```
docker run -d --network=reddit --network-alias=db  -v reddit_db:/data/db mongo:latest
docker run -d --network=reddit --network-alias=reddit-post  -e "POST_DATABASE_HOST=db" n3tdom/post:1.0
docker run -d --network=reddit --network-alias=reddit-comment  -e "COMMENT_DATABASE_HOST=db" n3tdom/comment:1.0
docker run -d --network=reddit -p 9292:9292 \
-e "POST_SERVICE_HOST=reddit-post" \
-e "COMMENT_SERVICE_HOST=reddit-comment" \
n3tdom/ui:2.0
```

### Задание со * #2: Пересобрать облегченные образы на базе alphine linux
TODO: Не выполнялось

## hw-10 docker-2
### Основное задание
```docker run --pid host``` #Запускает контейнер в неймспейсе docker host - из контейнера становятся видны процессы хоста.

### Задание со * - Docker + Terraform + Ansible + Packer
TODO: Не выполнялось

## hw-09 docker-1
### Основное задание
Установлен докер, знакомство с основными командами

### Задание со * - На основе вывода команд объясните чем отличается контейнер от образа

1. Единственная одинаковая для образа и контейнера секция в выводе docker inspect - содержит информацию о хосте и среде где создан image/container: hostname, attachStd, env, cmd, parent image.
2. Образ представляет из себя набор слоев, вывод команды указывает их список, название образа в репозитории, образ на основе которого он создавался
3. Контейнер являет собой уже готовый к запуску объект с сетевыми интерфейсами, маунтами и другими свойствами относительно docker daemon
