FROM php:5.4-fpm

RUN apt update
RUN apt upgrade -y
RUN apt install -y apt-utils
RUN apt install -y libmcrypt-dev

RUN docker-php-ext-install mysqli && \
    docker-php-ext-install pdo_mysql && \
    docker-php-ext-install mcrypt

