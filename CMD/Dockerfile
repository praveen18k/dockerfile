FROM almalinux:8
#almalinux is same as centos 
RUN yum install nginx -y 
RUN echo " Hello Welocome to Dockerfile" > /usr/share/nginx/html/hello.html
#this daemon off command makes our container running and attach to the screen 
CMD [ "nginx", "-g", "daemon off;"]
