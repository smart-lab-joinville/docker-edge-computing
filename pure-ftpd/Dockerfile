FROM gists/pure-ftpd:1.0.51

WORKDIR /etc/pureftpd

COPY pureftpd.passwd .

RUN pure-pw mkdb

WORKDIR /ftp/www

WORKDIR /
