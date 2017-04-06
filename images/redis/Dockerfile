FROM alpine:3.5
MAINTAINER fatrbaby "fatrbaby@qq.com"
RUN apk add --no-cache redis
ENTRYPOINT redis-server /etc/redis.conf
EXPOSE 6379