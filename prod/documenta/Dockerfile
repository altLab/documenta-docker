
FROM php:5-apache

MAINTAINER Pedro Angelo <pangelo@void.io>

COPY phile-cms/ /var/www/html/d

RUN chmod 777 /var/www/html/d/lib/cache/ && \
    a2enmod rewrite && \
    service apache2 restart

