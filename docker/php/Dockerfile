FROM php:8.2-apache

# Install system dependencies

WORKDIR /var/www/html

EXPOSE 8080 443 80

RUN apt-get update && apt-get install -y \
	libpq-dev

# Install PHP extensions
RUN docker-php-ext-install pdo_mysql mysqli pdo_pgsql

