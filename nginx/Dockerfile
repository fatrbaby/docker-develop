FROM nginx
MAINTAINER fatrbaby "fatrbaby@qq.com"
RUN mkdir -p /app && cp /etc/apt/sources.list /etc/apt/sources.list.bak
ADD conf.d/default.conf /etc/nginx/conf.d/default.conf
ADD sources.list /etc/apt/sources.list
RUN apt-get update -yqq
WORKDIR /app
EXPOSE 80