FROM centos:7
RUN yum -y update
RUN yum -y install httpd
COPY . /var/www/html/
WORKDIR /var/www/html/
EXPOSE 80
CMD httpd -D FOREGROUND
