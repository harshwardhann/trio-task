FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD="root"

ENV MYSQL_DATABASE="flask-db"

EXPOSE 3306

COPY CreateTable.sql docker-entrypoint-initdb.d/