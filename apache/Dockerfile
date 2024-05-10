FROM httpd:2.4.59

WORKDIR /usr/local/apache2/conf

COPY ./httpd.conf .

WORKDIR /usr/local/apache2/htdocs

COPY ./www .

WORKDIR /usr/local/apache2
