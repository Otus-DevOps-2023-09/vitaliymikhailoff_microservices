# vitaliymikhailoff_microservices  
vitaliymikhailoff microservices repository  

## Docker контейнеры. Docker под капотом.  

### Основное задание:  
Установлен Docker  
Протестированы основные команды Docker  
Развернута ВМ через ya cli  
Развернут Docker на ВМ через docker-machine  
Выполнена сборка образа для запуска приложения  
Выполнена загрузка образа на dockerhub  

## Docker образы. Микросервисы.  

### Основное задание:  
Скачаны файлы микросервисного проекта  
Созданы Dockerfileы для приложений  
Выполнена сборка образов для приложений  
Создана выделенная сеть для контейнеров приложений  
Создан volume для MongoDB  
Выполнены запуск и проверка проекта  

## Сетевое взаимодействие Docker контейнеров. Docker Compose. Тестирование образов.  

### Основное задание:  
Имя образа создается из названия папки и имени образа, можно переопределить при помощи ключа -p.  
Изучена работа сетей Docker  
Запущен проект reddit в Docker в одной сети с назначенными alias  
Запущен проект reddit в Docker с использованием нескольких сетей с назначенными alias  
Установлен docker compose  
Написан docker-compose.yml для проекта reddit  

## Устройство Gitlab CI. Построение процесса непрерывной интеграции  

### Основное задание:  
Развернута ВМ в YC  
Установлен Docker на ВМ  
Развернут GitLab в docker  
В GitLab созданы проект и группа  
Репозиторй GitLab подключен как удаленный реп  
Развернут и настроен раннер  
Выполнены проверка и тестирование пайплайнов gitlab-ci  

## Введение в мониторинг. Модели и принципы работы систем мониторинга  

### Основное задание:  
Развернута ВМ в YC  
Установлен Docker на ВМ 
Развернут Prometheus в docker  
Протестирован функционал Prometheus  
Создан отдельный образ Prometheus  
Собраны образы проекта reddit через скрипты  
Выполнен запуск проекта reddit и Prometheus через docker compose  
Протестирован функционал метрик Prometheus с остановкой сервиса  
Добавлен функционал node-exporter и протестирован  
Запушены образы в docker hub  
https://hub.docker.com/repository/docker/vitaliymikhailoff/prometheus/general  
https://hub.docker.com/repository/docker/vitaliymikhailoff/post/general  
https://hub.docker.com/repository/docker/vitaliymikhailoff/comment/general  
https://hub.docker.com/repository/docker/vitaliymikhailoff/ui/general  


## Введение в Kubernetes #1   

### Основное задание:  
Созданы деплоймент манифесты для приложений  
Создана ВМ в YC 
Развернут minikube (т.к. в методичке нет инструкции по развертке через kubeadm)  
Созданы деплойменты приложений в minikube - статус Running  

## Применение системы логирования в инфраструктуре на основе Docker     

### Основное задание: 
Развернута ВМ в YC  
Установлен Docker на ВМ  
Создан Dockerfile для системы логирования  
Созданы Dockerfile и конфиг для fluentd  
Cобран образ fluentd и запущен  
Запущены контейнеры системы логирования  
Настроена отправка логов в fluentd  
Изучен инструмент визуализации логов kibana  
Добавлены фильтры  
Добавлены grok-шаблоны  
Запущен и изучен сервис трейсинга zipkin  
