Docker commands
-----------------
docker images --> it will listdown the images the server
docker pull image-name:version --> download the image from docker hub if you did not mention version latest one
docker create image-id --> this will create docker container  
docker ps --> listdown the running containers
docker ps -a --> list down all containers including running/stopped/exited/created
docker start container-id --> to start the docker container 
docker stop container-id --> to stop the docker container
docker run = pull+create+start (insted of pullilg from docker hub and creating and staring use docker run) 
docker images rmi --> to remove all docker images from centos/server 
docker images -a -q --> -a to get all images and -q is nothing but ids of the images
docker rmi 'docker images -a -q' - > it will remove the image ids 
docker rm 'docker ps -a -q' -> rm is removing all containers ids 
docker rmi <image-id> -> removes perticular image  
docker run -p <host-port>:<container-port> image - > is docker image pulling+creating+starting+ports forwarding
docker run -d -- > detach the screen and run in background
docker run -d -p 8081:80 nginx -> this will run in background and you can work on screen
docker exec -it <container-id> bash --> now i am inside the container, i mean i logged in to container  
docker run -d --name mynginx -p 8080:80 nginx - > we can create container name as per our requirment
docker logs <container-id> - > to check the container logs
docker build -t image-name:version . --> to buid docker image, it means tagging the version