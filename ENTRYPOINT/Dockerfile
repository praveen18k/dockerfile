FROM almalinux:8
#almalinux is same as centos 
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo " Hello Welocome to Dockerfile-ENTRYPOINT" > /usr/share/nginx/html/index.html
#this daemon off command makes our container running and attach to the screen 
CMD [ "nginx", "-g", "daemon off;"]