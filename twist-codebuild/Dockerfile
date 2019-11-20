FROM alpine:3.6
RUN apk update && \
    apk add --no-cache nginx
ENTRYPOINT /usr/sbin/nginx -g 'daemon off;' -c /etc/nginx/nginx.conf
EXPOSE 80
