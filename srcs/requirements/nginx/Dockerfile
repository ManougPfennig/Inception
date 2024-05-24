FROM alpine:3.19.1
RUN  apt-get -y update && apt-get -y install nginx
COPY files/default /etc/nginx/sites-available/default
EXPOSE 9000
EXPOSE 443
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]