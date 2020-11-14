# ToDoList-Docker-Test

stammt aus Docker "getting started" -> "Our application"

## Build
> 
> docker build -t getting-started .
> 

"Finally, the -t flag tags our image. Think of this simply as a human-readable name for the final image. Since we named the image getting-started, we can refer to that image when we run a container."

## Run
> 
> docker run -dp 3000:3000 getting-started
> 

"Remember the -d and -p flags? We're running the new container in "detached" mode (in the background) and creating a mapping between the host's port 3000 to the container's port 3000. Without the port mapping, we wouldn't be able to access the application."

anschliessend zu finden unter http://localhost:3000


