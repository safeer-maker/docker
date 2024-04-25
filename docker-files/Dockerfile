FROM ubuntu

# RUN yum install apache2 -y
RUN apt-get update
RUN apt-get install  apache2 -y
RUN apt-get install  apache2-utils -y

CMD ["apachectl", "-D", "FOREGROUND"]