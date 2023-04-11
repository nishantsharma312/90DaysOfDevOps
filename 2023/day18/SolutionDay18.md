# Day 18 Task: Docker for DevOps

## To run Docker commands without sudo use the below command :
`sudo usermod -aG docker $USER`

[![HkQSxxS.md.png](https://iili.io/HkQSxxS.md.png)](https://freeimage.host/i/HkQSxxS)

### Task-1 (docker-compose)
 - Learn how to use the docker-compose.yml file, to set up the environment, configure the services and 
   links between different containers, and also to use environment variables in the docker-compose.yml file.
   
 1. Create a docker-compose.yaml file.
    
    [![HkZug6b.md.png](https://iili.io/HkZug6b.md.png)](https://freeimage.host/i/HkZug6b)
    
    [![HkZ5Snt.md.png](https://iili.io/HkZ5Snt.md.png)](https://freeimage.host/i/HkZ5Snt)
 
 2. Use `docker-compose up -d` command to build and run containers for multiple services with a single command.
 
    [![HkZYwIp.md.png](https://iili.io/HkZYwIp.md.png)](https://freeimage.host/i/HkZYwIp)
 
 3. Checking if containers are running with `docker ps` command and also on respective ports.
 
    [![HkZlFdg.md.png](https://iili.io/HkZlFdg.md.png)](https://freeimage.host/i/HkZlFdg)
    
    [![HkZ0PSe.md.png](https://iili.io/HkZ0PSe.md.png)](https://freeimage.host/i/HkZ0PSe)
    
    [![HkZEJB2.md.png](https://iili.io/HkZEJB2.md.png)](https://freeimage.host/i/HkZEJB2)
 
 4. Using `docker-compose down` command to stop and remove all services in 1 go.
   
    [![HkZMXzG.md.png](https://iili.io/HkZMXzG.md.png)](https://freeimage.host/i/HkZMXzG)
    
 ### Task-2 
 
- Pull a pre-existing Docker image from a public repository (e.g. Docker Hub) and run it on your local machine.

    [![HkZUBln.md.png](https://iili.io/HkZUBln.md.png)](https://freeimage.host/i/HkZUBln)
    
    [![HkZgNBS.md.png](https://iili.io/HkZgNBS.md.png)](https://freeimage.host/i/HkZgNBS)
    
    [![HkZ4Bl1.md.png](https://iili.io/HkZ4Bl1.md.png)](https://freeimage.host/i/HkZ4Bl1)

- Inspect the container's running processes and exposed ports using the docker inspect command.

    [![HkZie5X.md.png](https://iili.io/HkZie5X.md.png)](https://freeimage.host/i/HkZie5X)

- Use the docker logs command to view the container's log output.

    [![HkZLwAX.md.png](https://iili.io/HkZLwAX.md.png)](https://freeimage.host/i/HkZLwAX)

- Use the docker stop and docker start commands to stop and start the container.

    [![HkZZ7hg.md.png](https://iili.io/HkZZ7hg.md.png)](https://freeimage.host/i/HkZZ7hg)
    
    [![HkZtglR.md.png](https://iili.io/HkZtglR.md.png)](https://freeimage.host/i/HkZtglR)

- Use the docker rm command to remove the container when you're done.
    
    [![HkZD4qb.md.png](https://iili.io/HkZD4qb.md.png)](https://freeimage.host/i/HkZD4qb)
    
    


