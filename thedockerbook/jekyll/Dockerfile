FROM ubuntu:14.04
MAINTAINER zhangyue0503 "zhangyue0503@hotmail.com"
ENV REFRESHED_AT 2017-06-25

RUN apt-get -yqq update
RUN apt-get -yqq install ruby ruby-dev make nodejs
RUN gem install --no-rdoc --no-ri jekyll -v 2.5.3

VOLUME /data
VOLUME /var/www/html
WORKDIR /data

ENTRYPOINT ["jekyll","build","--destination=/var/www/html"]
