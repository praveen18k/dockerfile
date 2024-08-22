FROM nginx
#generally we have index.html in nginx, i wan tot remove that
RUN rm -rf /usr/share/nginx/html/index.html
#files should be available in current directory whre Dockerfile exists
# if you want to copy all files under one foler add / after folder e.g PI/
COPY index.html /usr/share/nginx/html/index.html 
