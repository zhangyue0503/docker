FROM ubuntu:14.04
MAINTAINER zhangyue0503 "zhangyue0503@hotmail.com"
ENV REFRESHED_AT 2017-06-25

RUN apt-get -yqq update
RUN apt-get -yqq install wget 

VOLUME ["/var/lib/tomcat7/webapps/"]
WORKDIR /var/lib/tomcat7/webapps/

ENTRYPOINT ["wget"]
CMD ["--help"]
