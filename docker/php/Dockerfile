FROM php:7.2-apache

RUN mv "$PHP_INI_DIR/php.ini-production" "$PHP_INI_DIR/php.ini" && docker-php-ext-install mysqli && a2enmod rewrite && a2enmod headers