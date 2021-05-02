FROM ubuntu:18.04
MAINTAINER Jossie
RUN apt-get update
RUN apt-get install -y apache2
EXPOSE 80
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]