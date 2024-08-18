FROM mysql:8.0.33

LABEL "Project"="Docker-WebApp"
LABEL "Author"="ItsNotRohit02"

ENV MYSQL_ROOT_PASSWORD="root-password"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql