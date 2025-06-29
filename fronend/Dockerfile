FROM nginx:mainline-alpine3.22-perl
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY scripts/* /usr/share/nginx/html/

