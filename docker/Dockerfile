FROM nginx:1.14-alpine
    
RUN mkdir -p /usr/share/nginx/html/ntest
COPY ./docker/nginx.conf /etc/nginx/conf.d/default.conf
ADD . /usr/share/nginx/html/ntest
RUN rm -rf /usr/share/nginx/html/ntest/docker
