FROM php:8.2-cli

COPY php.ini "${PHP_INI_DIR}/conf.d"

RUN pecl install xdebug\
    && docker-php-ext-enable xdebug
    
