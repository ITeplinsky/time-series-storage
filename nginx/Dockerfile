FROM nginx:1.25.2

RUN rm /etc/nginx/conf.d/default.conf

COPY ./my_conf.conf /etc/nginx/conf.d/default.conf

RUN sudo nginx -t

EXPOSE 27017


