FROM postgres:16.1-bullseye

ENV LC_ALL=en_US.UTF-8 \
    TZ=JST-9 \
    TERM=xtermdocker-attachingdocker-attaching

COPY ./docker/postgres/initdb /docker-entrypoint-initdb.d
