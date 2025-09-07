## Начальные требования

- Docker
- NodeJS >= 16

## Docker установка

https://docs.docker.com/get-docker/

### Backend установка

- Перейдите в директорию (выполнить из корня приложения)

`cd backend`

- Установите зависимости

`$ npm ci`

- Запуск сервера (для запуска необходима работающая база данных на порте :5432)

`$ npm start`

### Docker

`$ docker compose build`

`$ docker compose down -v`

`$ docker compose up`

Сервер будет доступен по адресу `localhost:3000`

Клиент будет доступен по адресу `localhost:8080`

## API документация (OpenAPI)

Документация доступна по адресу

```
http://localhost:3000/explorer/
```
