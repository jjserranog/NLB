FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d/default.conf
RUN mkdir -p /var/www/html/ && echo "Esto es la App1" >/var/www/html/index.html

