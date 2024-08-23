FROM almalinux:8
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
# ONBUILD will not execute when developer building his image 
ONBUILD ADD index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;"]