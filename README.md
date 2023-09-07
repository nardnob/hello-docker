# hello-docker
Practicing with Docker.

docker images are read-only and are ran within containers.

docker build -t hello-docker:1.0.0

docker run --name first-container -p 8080:80 hello-docker:1.0.0

docker ps -a  - displays containers

docker images

docker start b363

docker stop b363

docker rm b363

docker rmi 83b - removes image
