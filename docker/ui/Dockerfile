FROM ubuntu:latest
ENV DEBIAN_FRONTEND="noninteractive" TZ="America/Toronto"
RUN apt-get update
RUN apt-get install -y apache2
ADD index.html /var/www/html/
CMD /usr/sbin/apache2ctl -D FOREGROUND
EXPOSE 80