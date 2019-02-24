FROM ubuntu
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Our first Docker image for Nginx' > /usr/share/nginx/html/index.html
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
EXPOSE 80
