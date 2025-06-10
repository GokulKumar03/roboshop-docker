FROM mysql:5.7
ENV MYSQL_ROOT_PASSWORD=RoboShop@1 \
    YSQL_DATABASE=cities \
    MYSQL_USER=shipping \
    MYSQL_PASSWORD=secret
COPY scripts/* /docker-entrypoint-initdb.d/    
