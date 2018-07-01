FROM php:7.2-fpm

LABEL maintainer="Theo Tzaferis<t.tzfrs@gmail.com>"

RUN apt-get update && docker-php-ext-install -j$(nproc) pdo pdo_mysql
