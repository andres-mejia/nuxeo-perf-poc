FROM nginx:alpine

VOLUME ["/var/www/static"]

RUN rm -v /etc/nginx/nginx.conf

ADD nginx.conf /etc/nginx/

CMD ["nginx", "-g", "daemon off;"]
