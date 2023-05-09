Docker with logger app
=====================

Usage
-----

Build container
```bash
docker-compose build
```
Build start with detach mode
```bash
docker-compose up -d
```
log to the php-fpm container
```bash
docker exec -it logger-php bash
```
Run composer
```bash
composer install
```

Instruction on how to run the app can be found [here](./app/README.md)


