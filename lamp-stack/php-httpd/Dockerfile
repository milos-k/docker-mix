FROM php:7.3-apache
RUN apt-get update && apt-get install -y default-mysql-client
RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN docker-php-ext-enable mysqli
