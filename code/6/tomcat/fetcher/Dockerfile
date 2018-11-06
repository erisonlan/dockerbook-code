FROM ubuntu
LABEL maintainer="james@example.com"
ENV REFRESHED_AT 2018-11-06

RUN apt-get -qq update
RUN apt-get -qq install wget

VOLUME [ "/var/lib/tomcat7/webapps/" ]
WORKDIR /var/lib/tomcat7/webapps/

ENTRYPOINT [ "wget" ]
CMD [ "--help" ]
