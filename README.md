# nodeappweb
#docker
docker build -t <image-name>
docker run -d <image-name>
OR
docker run -it -p 8080:8080 <image-name>
#docker running containers
docker ps
#docker stoped conainers
docker ps -a
#To list the docker images
docker images
#To enter into docker  container
docker exec -it <containerid>
#To stop the docker container
docker rm -f <containerid>
#To Delete the docker image
docker rmi -f <imagesid>
