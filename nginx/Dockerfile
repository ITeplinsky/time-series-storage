FROM nginx:1.25.2

RUN rm /etc/nginx/conf.d/default.conf

COPY ./for_docker.conf /etc/nginx/conf.d/default.conf

RUN sudo nginx -t

