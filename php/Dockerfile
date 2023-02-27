FROM php:8.0-fpm
COPY php.ini /usr/local/etc/php/php.ini
COPY www.conf /usr/local/etc/php-fpm.d/zzz-www.conf
RUN docker-php-ext-install pdo_mysql