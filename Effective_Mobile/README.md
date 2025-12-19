# Nginx + Backend (Docker Compose)

## Описание

Проект разворачивает простое веб-приложение, доступное пользователю через Nginx.
Nginx работает как reverse proxy и проксирует запросы к backend-сервису,
работающему внутри Docker-сети.

Схема:
nginx → backend

---

## Запуск проекта

Требования:

* Docker
* Docker Compose

Запуск:

docker compose up --build
