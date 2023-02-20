# docker-commands
cmd: to list down docker images available
```bash 
docker image ls
```
cmd: to get list of containers
```bash 
docker ps -a
```
cmd: to delete the containers
```bash
docker rm container_id
```

cmd: to delete all the container
```bash
docker rm $(docker ps -a -q)
```
cmd: to delete the image id
```bash
docker rmi image_id
```
