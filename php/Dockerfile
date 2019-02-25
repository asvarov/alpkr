FROM php:5.6-apache
RUN docker-php-ext-install mysql
CMD echo "ServerName alpkr.dp.ua" >> /etc/apache2/apache2.conf
CMD echo "ServerName alpkr.dp.ua" >> /etc/httpd/conf/httpd.conf
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
