Docker with logger app
=====================

Usage
-----

Download app
```bash 
git clone git@github.com:jakubBab/logger-app.git app
```

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

Instruction on how to run the app can be found [here](https://github.com/jakubBab/logger-app/blob/master/README.md)


