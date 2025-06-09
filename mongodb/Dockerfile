FROM mongo:5
COPY *.js /docker-entrypoint-initdb.d/
# docker-entrypoint-initdb.d --> This means When we are keeping some js scripts, mongodb will load it automatically.