FROM nginx:1.25.2

RUN rm /etc/nginx/conf.d/default.conf

COPY ./my_conf.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

RUN apt-get update && \
      apt-get -y install sudo

RUN sudo nginx -t 

RUN sudo service nginx restart

