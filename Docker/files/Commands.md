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
- Will you loose your data, when a docker container exists.
- Where all do you think Docker is being used.
- How Docker is different from other containerization methods.
- Can I use JSON instead of YAML for my Compose file in Docker.
- Have you used Docker in your previous position.
- How far do Docker containers scale.Are there any requirement for the same.
- What platforms does Docker run on.
- Can you remove a paused container from Docker.
- Can container restart itself.
- Is it better to remove the container directly using rm command or stop the container followed by remove container.
- How many containers can run per host.
- Is it good practice to run stateful applications on Docker.
- Suppose you have an application that has many dependent services. Will Docker compose wait for current container to be ready to move to the running of the next service.
- How will you monitor Docker in production.
- Is it good practice to run Docker compose in production.
- What changes are expected in your Docker compose file while moving it to production.
- Are you aware of load balancing across containers and host.How does it works.