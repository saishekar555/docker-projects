# Docker Commands

## List Containers
docker ps

## List Images
docker images

## Build Image
docker build -t myimage .

## Run Container
docker run -d -p 80:80 nginx

## View Logs
docker logs container_name

## Open Container Shell
docker exec -it container_name bash
