FROM nginx:alpine

MAINTAINER Vaibhav Gupta

COPY  nginx.conf /etc/nginx/
COPY  nginx.conf.default /etc/nginx/conf.d/default.conf

COPY  key.pem /etc/nginx/
COPY  cert.pem /etc/nginx/

COPY testdata.txt /usr/share/nginx/html/

COPY TestPage.html /usr/share/nginx/html/index.html