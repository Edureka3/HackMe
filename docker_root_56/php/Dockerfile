FROM php:7.3-apache

RUN echo "Building image"

RUN apt-get update

RUN apt-get update && apt-get install -y iputils-ping

RUN docker-php-ext-install mysqli


