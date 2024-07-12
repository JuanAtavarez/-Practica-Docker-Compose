# Usa la imagen base de Apache con PHP 
FROM php:7.4-apache 
RUN a2enmod rewrite 
COPY ./mi-aplicacion /var/www/html 
RUN chown -R www-data:www-data /var/www/html && chmod -R 755 /var/www/html 
