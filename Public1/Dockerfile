FROM httpd
RUN apt-get update
RUN apt-get install -y vim net-tools iputils-ping curl
COPY ./index.html /usr/local/apache2/htdocs/index.html
