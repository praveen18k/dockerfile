FROM almalinux:8
RUN yum install nginx -you
RUN echo "Hello, welcome to Dockerfile." > /usr/share/nginx/html/hello.html 
CMD [ "nginx","-g", "daemon off;" ]
