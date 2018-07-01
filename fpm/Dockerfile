FROM php:7.2-fpm

LABEL maintainer="Theo Tzaferis<t.tzfrs@gmail.com>"

USER root

RUN rm /usr/local/etc/php-fpm.d/docker.conf \
    && rm /usr/local/etc/php-fpm.d/www.conf \
    && rm /usr/local/etc/php-fpm.d/www.conf.default \
    && rm /usr/local/etc/php-fpm.d/zz-docker.conf \
    && rm -rf /var/www/html

ADD app.pool.conf /usr/local/etc/php-fpm.d/app.pool.conf
