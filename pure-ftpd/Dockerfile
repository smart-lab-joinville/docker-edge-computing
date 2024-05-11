FROM gists/pure-ftpd:1.0.51

WORKDIR /etc/pureftpd

COPY pureftpd.passwd .

RUN pure-pw mkdb

WORKDIR /ftp/www

RUN chmod 777 /ftp/www

WORKDIR /
