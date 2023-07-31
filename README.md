# docker-genz-training-session

# Docker Containers
## _Practical Guide_

[![N|Solid](https://www.devopsmadness.com/images/dockerventure_1/docker_logo.png)](https://github.com/amraabdallah/docker-genz-training-session)



## Common Commands

Run your first container
```sh
docker container run -it ubuntu:latest /bin/bash
```

List all images
```sh
docker image ls
```

Pull the ubuntu:latest image
```sh
docker image pull ubuntu:latest
```

Attach a new proccess to a running container
```sh
docker container exec -it <containername> bash
```

Stop a running container
```sh
docker container stop <containername||containerID>
```

Start a stopped container
```sh
docker container start <containername>
```

Delete a stopped container
```sh
docker container rm <containername>
```


> Note: You can exit a container without terminating it: `Ctrl-PQ`
  
