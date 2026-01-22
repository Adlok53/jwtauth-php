# jwtauth-php

1. Запустить контейнер
```
    docker compose up -d
```
2. Застановить зависимости
```
    docker exec -it project_app bash
    npm install
    composer install
```
3. Установить права пользователя
```
    docker exec -it project_app bash
    chmod 777 -R ./
```
4. Сделать миграция базы данных
```
    docker exec -it project_app bash
    php artisan migrate
```