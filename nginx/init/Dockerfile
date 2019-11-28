FROM nginx

RUN rm /etc/nginx/conf.d/default.conf
COPY proxy_server_api.conf  /etc/nginx/conf.d/
RUN mkdir -p /usr/share/nginx/Proxy_Server/static


