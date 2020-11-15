FROM ubuntu:latest

RUN apt-get -y update && \
    apt-get install -y apache2 

ENTRYPOINT ["/usr/sbin/apache2"]
CMD ["-D", "FOREGROUND"]
