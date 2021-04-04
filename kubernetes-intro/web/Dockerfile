FROM nginx
RUN useradd -u 1001 www-user
RUN mkdir /app && chown -R www-user:www-user /app/
COPY ./hw1.conf /etc/nginx/conf.d/hw1.conf
COPY ./nginx.conf /etc/nginx/nginx.conf
EXPOSE 8000
