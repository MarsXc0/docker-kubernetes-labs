FROM httpd:latest

RUN sed -i 's/Listen 80/Listen 8080/' /usr/local/apache2/conf/httpd.conf

RUN rm -rf /usr/local/apache2/htdocs/*

COPY index.html /usr/local/apache2/htdocs/
