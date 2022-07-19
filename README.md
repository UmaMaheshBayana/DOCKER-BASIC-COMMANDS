# DOCKER BASIC COMMANDS

**Command to pull the image from docker hud (pulls the image from repository to local environment)**

```docker pull $imagename```

**Command to Download Docker image**

```docker run $imagename```

**Command to run Docker image in detached mode**

```docker run -r $imagename```

**Command to check docker containers**

```docker ps```

**Command to start docker container**

```docker start $containerID or $name```

**Command to stop docker container**

```docker stop $containerID or $name```

**Command to check all the running and stopped containers**

```docker ps -a```

**Command to run docker image with specific image version**

```docker run $image:version```

**Command to run doker image with user-defined port**

```docker run -p$DefinedPort:$ImageDefaultPort -d $imagename:version```

**Command to run  docker image with user defined port and user defined image name**

```docker run -d -p$DefinedPort:$ImageDefaultPort --name $definedName $image:version```

**Command to Check Container logs**

```docker logs $containerID or $ContainerName```

**Command to interact with container terminal**

```docker exec -it $containerID /bin/bash```
