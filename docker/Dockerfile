# docker/DockerFile

FROM nginx:1.17.8-alpine
LABEL version="1.0"
LABEL maintainer="kjkandrea@gmail.com"
LABEL Desciption="nginx:1.17.8-alpine + centos user + supervisor, shopby-nginx:1.17.8-alpine"

ARG WEB_ROOT=/home/centos/my-app
ARG NGINX_ROOT=/etc/nginx

COPY app $WEB_ROOT
COPY nginx.conf $NGINX_ROOT/nginx.conf