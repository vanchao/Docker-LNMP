FROM php:7.3-fpm
RUN apt-get update && apt-get install -y \
libfreetype6-dev \
libjpeg62-turbo-dev \
libpng12*-dev \
libmagickwand-dev \
&& pecl install imagick \
&& docker-php-ext-enable opcache \
&& docker-php-ext-install pdo_mysql \
&& docker-php-ext-install gd \
&& docker-php-ext-install mysqli \
&& docker-php-ext-enable imagick \
