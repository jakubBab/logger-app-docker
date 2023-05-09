FROM php:8.1-fpm
ARG TIMEZONE

RUN apt-get update && apt-get install -y \
    openssl \
    git \
    unzip

# Install Composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
RUN composer --version

RUN mkdir -p -m 777 /var/www/.composer

RUN usermod -u 1000 www-data

USER www-data

WORKDIR /var/www/app
