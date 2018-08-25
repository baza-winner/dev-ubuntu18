
# Описание

Проект по сборке базового образа `dev-ubuntu18`, используемого в dev-docker-контейнерах проектов [baza-winner](https://github.com/baza-winner)

# Настройка окружения

1. [Установить команду bw](https://github.com/baza-winner/bw/wiki)

2. Развернуть рабочее место проекта `dubu18` (`dev-ubuntu18`)

```
bw project dubu18
```
 
# Использование

## Сборка образа

```
dubu18 docker build
```

## Push образа

```
_docker login
dubu18 docker push
```
