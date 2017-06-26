FROm ubuntu:14.04
MAINTAINER zhangyue0503 "zhangyue0503@hotmail.com"
ENV REFRESHED_AT 2017-06-25

RUN apt-get -yqq update
RUN apt-get -yqq install software-properties-common python-software-properties
RUN add-apt-repository ppa:chris-lea/redis-server
RUN apt-get -yqq update 
RUN apt-get -yqq install redis-server redis-tools

VOLUME ["/var/lib/redis","/var/log/redis"]

EXPOSE 6379
CMD []
