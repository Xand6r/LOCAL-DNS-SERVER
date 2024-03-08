FROM nginx:latest

RUN apt-get update && apt-get install -y procps

COPY ./html/ /usr/share/nginx/html/
