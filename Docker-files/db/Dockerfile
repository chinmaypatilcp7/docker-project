FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "author"="chinmay"
ENV MYSQL_ROOT-PASSWORD="vprodpass"
ENV MYSQL_DATABASE="accounts"
ADD db.backup.sql /docker-entrypoint-initdb.d