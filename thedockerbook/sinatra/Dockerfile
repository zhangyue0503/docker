FROM ubuntu:14.04
MAINTAINER zhangyue0503 "zhangyue0503@hotmail.com"
ENV REFRESHED_AT 2017-06-24

RUN apt-get update -y && apt-get -qq install ruby ruby-dev build-essential redis-tools
RUN gem install --no-rdoc --no-ri sinatra json redis
RUN mkdir -p /opt/webapp

EXPOSE 4567

CMD ["/opt/webapp/bin/webapp"]
