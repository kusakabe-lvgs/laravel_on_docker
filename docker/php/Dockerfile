FROM php:7.3.7-fpm-alpine3.10
COPY php.ini /usr/local/etc/php/

RUN cd /usr/bin && curl -s http://getcomposer.org/installer | php && ln -s /usr/bin/composer.phar /usr/bin/composer

RUN docker-php-ext-install pdo_mysql
