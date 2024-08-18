FROM nginx

LABEL "Project"="Docker-WebApp"
LABEL "Author"="ItsNotRohit02"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/app.conf