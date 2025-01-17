# Day 19 Task: Docker for DevOps

## Task-1

- Create a multi-container docker-compose file which will bring *UP* and bring *DOWN* containers in a single shot

  [![HvH46IS.md.png](https://iili.io/HvH46IS.md.png)](https://freeimage.host/i/HvH46IS)
  
- Use the `docker-compose up` command with the `-d` flag to start a multi-container application in detached mode.

  [![HvH63Eg.md.png](https://iili.io/HvH63Eg.md.png)](https://freeimage.host/i/HvH63Eg)
  
- Use the `docker-compose scale` command to increase or decrease the number of replicas for a specific service.

  1. Adding replicas and ports in yaml file.
  
    [![HvH6A4s.md.png](https://iili.io/HvH6A4s.md.png)](https://freeimage.host/i/HvH6A4s)
  
  2. Using scale command.

    [![HvH6lu2.md.png](https://iili.io/HvH6lu2.md.png)](https://freeimage.host/i/HvH6lu2)
    
- Use the `docker-compose logs` to view the logs of a specific service.

  1. Logs for all services.
  
     [![HvH6sup.md.png](https://iili.io/HvH6sup.md.png)](https://freeimage.host/i/HvH6sup)
  
  2. Logs for a specific service.

     [![HvH6LwN.md.png](https://iili.io/HvH6LwN.md.png)](https://freeimage.host/i/HvH6LwN)
     
- Use the `docker-compose down` command to stop and remove all containers, networks, and volumes associated with the application

  [![HvH6DMX.md.png](https://iili.io/HvH6DMX.md.png)](https://freeimage.host/i/HvH6DMX)
  
  
## Task-2 (Docker volumes)

- Creating Docker volumes

  [![HvJ2gvp.md.png](https://iili.io/HvJ2gvp.md.png)](https://freeimage.host/i/HvJ2gvp)
  
- Mounting volume to a container.

  [![HvJ39uS.md.png](https://iili.io/HvJ39uS.md.png)](https://freeimage.host/i/HvJ39uS)
  
- Verify using exec command that volume is connected.

  [![HvJ3oAB.md.png](https://iili.io/HvJ3oAB.md.png)](https://freeimage.host/i/HvJ3oAB)
  
- Use the docker volume ls command to list all volumes and docker volume rm command to remove the volume when you're done.

  1. `docker volume ls`
 
     [![HvJFogf.md.png](https://iili.io/HvJFogf.md.png)](https://freeimage.host/i/HvJFogf)
 
  2. `docker volume rm <container ID>`

     [![HvJFTe2.md.png](https://iili.io/HvJFTe2.md.png)](https://freeimage.host/i/HvJFTe2)
     
- we can also add volumes in docker-compose.yaml file.

   [![HvJFSmN.md.png](https://iili.io/HvJFSmN.md.png)](https://freeimage.host/i/HvJFSmN)
  
