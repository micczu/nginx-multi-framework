FROM php:5.6-fpm

RUN docker-php-ext-install pdo pdo_mysql mysqli

WORKDIR /var/www/

CMD ["php-fpm"]

EXPOSE 9000