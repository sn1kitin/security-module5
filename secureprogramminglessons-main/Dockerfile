FROM --platform=linux/amd64 php:8.1-apache
RUN docker-php-ext-install pdo pdo_mysql
COPY . /var/www/html/
