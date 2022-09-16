FROM  nginx:latest

COPY ./conf.d/default.conf /etc/nginx/conf.d/default.conf
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./html /var/www/
COPY ./assets /var/resorce/assets/

EXPOSE 80 