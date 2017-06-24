FROM ubuntu:14.04
MAINTAINER zhangyue "zhangyue0503@hotmail.com"
ENV REFRESHED_AT 20160622
RUN apt-get -y update && apt-get -y install nginx
RUN mkdir -p /var/www/html/website
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
