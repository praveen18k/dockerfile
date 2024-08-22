FROM almalinux:8
RUN yum instal nginx -y
# by default it is tcp protocol 
EXPOSE 80/tcp 
# daemon off command makes our container running and attached to screen
CMD [ "nginx", "-g", "daemon off" ]