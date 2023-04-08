# Day 16 Task: Docker for DevOps


## Task - To run some basic docker commands

- `docker pull [image-name]` To pull the docker image from the registry (DockerHub).

   [![image](https://www.linkpicture.com/q/1_592.png)](https://www.linkpicture.com/view.php?img=LPic6431836129ca4857609193)

- `docker images` To view all the docker images on the docker host.

   [![image](https://www.linkpicture.com/q/2_1299.png)](https://www.linkpicture.com/view.php?img=LPic643184c9131c7134358008)  
  
- `docker run -d [image-name or ID]` To Create a container using an image.
  `docker ps` This command is used to list the running containers.

   [![image](https://www.linkpicture.com/q/3_895.png)](https://www.linkpicture.com/view.php?img=LPic643186384cb6c1790916083)
   
- `docker exec -it [container-name or containerID] bash` To log in to the running container (To log-in container should be in running state).

   [![image](https://www.linkpicture.com/q/4_700.png)](https://www.linkpicture.com/view.php?img=LPic6431874623d2273629066)
   
- `docker inspect [container-name or ID]` docker inspect is a command that returns detailed, low-level information on Docker objects. 
   Those objects can be docker images, containers, networks, volumes, plugins, etc. By default, docker inspect returns information in JSON format.
   
   [![image](https://www.linkpicture.com/q/5_519.png)](https://www.linkpicture.com/view.php?img=LPic6431885c2c25d1614066269)
   
- `docker port [container-name or ID]` To list the port mappings for a container.

   [![image](https://www.linkpicture.com/q/Screenshot-from-2023-04-08-20-00-35.png)](https://www.linkpicture.com/view.php?img=LPic643189127c93f679365017)
   
- `docker stats [container-name or containerID]` The docker stats command returns a live data stream for running containers. 
   To limit data to one or more specific containers, specify a list of container names or ids separated by a space. You can 
   specify a stopped container but stopped containers do not return any data.
   
   [![image](https://www.linkpicture.com/q/Screenshot-from-2023-04-08-20-02-38.png)](https://www.linkpicture.com/view.php?img=LPic643189ad0c9352120635456)
   
- `docker top [container-name or containerID]` To view the processes running inside a container.

   [![image](https://www.linkpicture.com/q/Screenshot-from-2023-04-08-20-04-30.png)](https://www.linkpicture.com/view.php?img=LPic64318a1b7becc1462776033)
   
- `docker save -o [image-name].tar [image-name]` To save an image to a tar archive.

   [![image](https://www.linkpicture.com/q/Screenshot-from-2023-04-08-20-09-25.png)](https://www.linkpicture.com/view.php?img=LPic64318ae84fbb71638641434)
   
- `docker load -i [image-name].tar` To load an image from a tar archive.

   [![image](https://www.linkpicture.com/q/Screenshot-from-2023-04-08-20-11-59.png)](https://www.linkpicture.com/view.php?img=LPic64318bbc1624a539152070)
   
- `docker start/stop [container-name or ID]` To Start/Stop a container.

   [![image](https://www.linkpicture.com/q/Screenshot-from-2023-04-08-20-12-19.png)](https://www.linkpicture.com/view.php?img=LPic64318c3f8fa99582790292)
