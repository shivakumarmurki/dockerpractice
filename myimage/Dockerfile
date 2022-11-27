
FROM nginx:latest

RUN apt-get update
RUN apt-get install curl -y
RUN apt-get install tree -y

COPY index.html /usr/share/nginx/html/
