FROM python:3.6-slim
MAINTAINER "Type your name."
RUN mkdir /var/www
COPY index.html /var/www
WORKDIR /var/www
CMD python -m http.server 80
