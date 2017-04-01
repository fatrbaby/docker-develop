FROM alpine:3.5
MAINTAINER fatrbaby "fatrbaby@qq.com"
RUN apk add --no-cache redis
ADD redis.conf /etc/redis.conf
ENTRYPOINT redis-server /etc/redis.conf
EXPOSE 6379