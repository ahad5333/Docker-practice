Here's the `README.md` file with all the 14 Docker commands formatted appropriately:

```markdown
# Docker In One Shot - Part 1

This guide summarizes the key Docker commands demonstrated in the video.

## Commands Used

### 1. Check Docker Installation
To verify Docker is installed and check the available Docker commands:
```bash
docker
```

### 2. Run an Ubuntu Container
To run an Ubuntu container interactively:
```bash
docker run -it ubuntu
```

### 3. Exit the Container
To exit the running container:
```bash
Ctrl + D
```

### 4. Run the Ubuntu Container Again
To run the Ubuntu container interactively again:
```bash
docker run -it ubuntu
```

### 5. List All Running Containers
To list all currently running Docker containers:
```bash
docker ps
```

### 6. List All Containers (Running and Stopped)
To list all containers, including those that are stopped:
```bash
docker ps -a
```

### 7. Remove a Specific Container
To remove a specific container using its container ID:
```bash
docker rm <container_id>
```

### 8. Remove All Stopped Containers
To remove all stopped containers:
```bash
docker container prune
```

### 9. List Docker Images
To list all Docker images on the local machine:
```bash
docker images
```

### 10. Remove a Specific Docker Image
To remove a specific Docker image using its image ID:
```bash
docker rmi <image_id>
```

### 11. Pull a Docker Image
To pull a specific Docker image from Docker Hub:
```bash
docker pull <image_name>
```

### 12. Start a Stopped Container
To start a container that has been stopped:
```bash
docker start <container_id>
```

### 13. Stop a Running Container
To stop a running container:
```bash
docker stop <container_id>
```

### 14. Run a Command in a Running Container
To execute a command inside a running container:
```bash
docker exec -it <container_id> <command>
```

## Notes

- Replace `<container_id>` and `<image_id>` with the actual IDs of your containers and images.
- Replace `<image_name>` with the name of the image you want to pull.
- The `-it` flag in the `docker run` command allows you to interact with the container using a terminal interface.

For more detailed information on Docker commands, refer to the official [Docker documentation](https://docs.docker.com/).
```

You can add this content to your `README.md` file in your GitHub repository.