FROM php:8.0-apache
COPY ./php.ini /usr/local/etc/php/

RUN apt-get update \
  && apt-get install -y docker-php-ext-install pdo_mysql mysqli mbstring