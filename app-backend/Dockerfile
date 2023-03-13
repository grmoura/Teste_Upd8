FROM wyveo/nginx-php-fpm:php81

EXPOSE 8000
RUN mkdir -p /var/log/nginx/
RUN mkdir -p /var/www/
RUN chmod -R 777 /var/log/nginx/
RUN chmod -R 777 /var/www/
COPY ./nginx.conf  /etc/nginx/conf.d
