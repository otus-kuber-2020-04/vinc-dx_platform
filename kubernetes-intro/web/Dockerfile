FROM nginx:1.18.0-alpine
RUN apk --no-cache add shadow && \
    usermod -u 1001 nginx && \
    groupmod -g 1001 nginx
ADD default.conf /etc/nginx/conf.d/default.conf
