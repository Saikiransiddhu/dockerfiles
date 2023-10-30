From almalinux:8
#almaliux is same as centos
RUN yum install nginx -y
RUN echo "Hello, Welcome to Dockerfile. A way of creating own images" > /usr/share/nginx/hello.html
# daemon command makes our container running and attached to screen
CMD [ "nginx", "-g", "daemon off" ]