FROM ubuntu:18.04
MAINTAINER Jossie
RUN apt-get update
RUN apt-get install -y siege
CMD ["siege","-b","http://apache"]