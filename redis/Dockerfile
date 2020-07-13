FROM redis:6.0.5

LABEL maintainer="honggenxiang <honggenxiang@hotmail.com>"

RUN mkdir /config && mkdir /redis-data

COPY config/redis.conf /config/redis.conf
COPY config/redis-cluster.conf /config/redis-cluster.conf

EXPOSE 7000