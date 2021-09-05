FROM nginx:1.14.2
COPY dist/web/ /usr/share/nginx/html/
COPY docker/default.conf /etc/nginx/conf.d/default.conf
RUN echo 'Started'