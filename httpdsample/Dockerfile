#FROM httpd
#EXPOSE 80
#LABEL THIS IS SAMPLE APP
#MAINTAINER PAVAN
#COPY index.html /usr/local/apache2/htdocs/
FROM httpd:2-alpine
EXPOSE 80
RUN rm -rf /usr/local/apache2/htdocs/
COPY index.html /usr/local/apache2/htdocs/
