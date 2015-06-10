FROM debian:jessie

<!-- @import maintainer -->
ENV EXTRA_DEPS "libjpeg62 libicu52 libmagickwand-6.q16-2"
ENV PHP_VERSION 5.4.40
ENV PHP_INI_DIR /usr/local/etc/php
ENV PHP_URL "http://php.net/get/php-$PHP_VERSION.tar.bz2/from/this/mirror"
ENV PHP_EXTRA_EXT "--enable-intl"
ENV PHP_EXTRA_BUILD_DEPS "libicu-dev"
ENV XDEBUG_BRANCH "xdebug_2_3"
<!-- @import ci-installation -->
