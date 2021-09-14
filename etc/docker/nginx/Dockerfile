FROM nginx:alpine

WORKDIR /var/www

COPY nginx/nginx.conf /etc/nginx/nginx.conf
COPY nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf
COPY nginx/sites-available/default.conf /etc/nginx/sites-available/default.conf

CMD ["nginx"]

EXPOSE 80 443