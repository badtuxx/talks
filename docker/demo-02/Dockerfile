FROM ubuntu
MAINTAINER jeferson@codeops.com.br

RUN apt-get update \
    && apt-get install -y nginx \
    && apt-get clean

COPY index.html /var/www/html/

ENV jeferson lindo

VOLUME /var/www/html

CMD /usr/sbin/nginx -g 'daemon off;'

EXPOSE 80
