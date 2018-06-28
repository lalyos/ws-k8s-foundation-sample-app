FROM openresty/openresty:alpine

RUN apk add --no-cache curl bash perl
ENV PATH="${PATH}:/usr/local/openrest"

ADD default.conf /etc/nginx/conf.d/default.conf
ADD nginx.conf /usr/local/openresty/nginx/conf/nginx.conf
