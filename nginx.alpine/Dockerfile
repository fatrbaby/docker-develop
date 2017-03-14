FROM alpine:3.5
MAINTAINER fatrbaby "fatrbaby@qq.com"
RUN apk add --no-cache nginx && mkdir -p /app
WORKDIR /app
EXPOSE 80 443
CMD ["nginx", "-g", "daemon off;"]