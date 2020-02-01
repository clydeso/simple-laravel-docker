# Simple Laravel Docker setup

## Requirements

- __[Download Docker](https://docs.docker.com/docker-for-mac/install/)__
- __[Download Composer](https://getcomposer.org/)__
- __[Laravel ^6.x](https://laravel.com/docs/6.x)__

## Setup

```
docker-compose build && docker-compose up -d
composer create-project --prefer-dist laravel/laravel my-app
```

## Containers

- PHP 7 (port:8080)
- NGINX (port:9000)
- MYSQL (port: 3306)
