- How to check for Docker client and Docker server version.
    ```
    docker version
    ```
- How do you get number of Containers Running, Paused and Stopped.
    ```docker info```
- How will you get help for any command.
    ```docker --help ```
    ```docker <command> --help```
- How to login into docker repository.
    ```docker login```
- How to get image from repo.
    ```docker pull <image_name>```
- How do you create a docker container from an image.
    ```docker run -it -d <image_name>```
- What does -d flag mean in above command.
- How do you list all running containers.
    ```docker ps```
- How do you access a running container.
    ```docker exec -it <container_id> bash```
- How to start a container.
    ```docker start <container_id>```
- How to stop a container.
    ```docker stop <container_id>```
- How to kill a container.
    ```docker stop <container_id>```
- Can you use a container, edit it and update it. Also how do you make it a new and store it on a local system.
    ```docker commit <container_id> <username/imagename>```
- How to push an image to Docker Hub.
    ```docker push <username/imagename>```
- How to delete a stopped container.
    ```docker rm <container_id>```
- How to delete an image from local storage system.
    ```docker rmi <image_id>```
- How to build a Dockerfile.
    ```docker build <path_to_docker_file>```
- Why docker system prune is used.What does it do.
    ```docker system prune```