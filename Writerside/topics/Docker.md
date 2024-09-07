# Docker

## Basic

**Check Docker version**
  ```bash
  docker --version
  ```

**List all running containers**
  ```bash
  docker ps
  ```

**List all containers (running and stopped)**
  ```bash
  docker ps -a
  ```

**Start a container**
  ```bash
  docker start <container_id>
  ```

**Stop a running container**
  ```bash
  docker stop <container_id>
  ```

**Remove a container**
  ```bash
  docker rm <container_id>
  ```

**Remove a running container (force)**
  ```bash
  docker rm -f <container_id>
  ```

**Pull an image from Docker Hub**
  ```bash
  docker pull <image_name>
  ```

**List all images**
  ```bash
  docker images
  ```

**Remove an image**
  ```bash
  docker rmi <image_id>
  ```

**Run a container (create and start)**
  ```bash
  docker run <image_name>
  ```

**Run a container with interactive shell**
  ```bash
  docker run -it <image_name> /bin/bash
  ```

**Run a container in detached mode (background)**
  ```bash
  docker run -d <image_name>
  ```

**Run a container with port mapping**
  ```bash
  docker run -p <host_port>:<container_port> <image_name>
  ```

**Run a container with volume mapping**
  ```bash
  docker run -v <host_path>:<container_path> <image_name>
  ```

**Show logs of a container**
  ```bash
  docker logs <container_id>
  ```


## Docker Compose

**Start services defined in docker-compose.yml**
  ```bash
  docker-compose up
  ```

**Start services in detached mode**
  ```bash
  docker-compose up -d
  ```

**Stop services**
  ```bash
  docker-compose down
  ```

**View running services**
  ```bash
  docker-compose ps
  ```

**Rebuild services**
  ```bash
  docker-compose up --build
  ```

**Show logs of services**
  ```bash
  docker-compose logs
  ```


## Docker Image & Containers

**Build an image from a Dockerfile**
  ```bash
  docker build -t <image_name> .
  ```

**Tag an image**
  ```bash
  docker tag <image_id> <repository_name>:<tag>
  ```

**Push an image to Docker Hub**
  ```bash
  docker push <repository_name>:<tag>
  ```

**Save an image to a tar archive**
  ```bash
  docker save -o <file_name>.tar <image_name>
  ```

**Load an image from a tar archive**
  ```bash
  docker load -i <file_name>.tar
  ```


## Container Interaction

**Enter a running container’s shell**
  ```bash
  docker exec -it <container_id> /bin/bash
  ```

**Copy files from container to host**
  ```bash
  docker cp <container_id>:/path/to/file /host/path
  ```

**Copy files from host to container**
  ```bash
  docker cp /host/path <container_id>:/path/to/file
  ```


## Docker Networks

**List Docker networks**
  ```bash
  docker network ls
  ```

**Create a network**
  ```bash
  docker network create <network_name>
  ```

**Connect a container to a network**
  ```bash
  docker network connect <network_name> <container_id>
  ```

**Disconnect a container from a network**
  ```bash
  docker network disconnect <network_name> <container_id>
  ```

