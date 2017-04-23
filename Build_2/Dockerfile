FROM nginx:1.10

RUN mkdir -p /var/www/html

WORKDIR /var/www/html

COPY nginx.conf /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]
