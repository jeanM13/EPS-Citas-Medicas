FROM mysql:8.0

ENV MYSQL_ALLOW_EMPTY_PASSWORD=NONE

COPY bd.sql /docker-entrypoint-initdb.d/1.sql

CMD ["mysql"]