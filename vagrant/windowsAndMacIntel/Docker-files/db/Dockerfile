FROM mysql:8.0.33
LABEL "Project"="VProject"
LABEL "Author"="Rahadian"
LABEL "description"="Containerization Project"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-init.db/db_backup.sql
