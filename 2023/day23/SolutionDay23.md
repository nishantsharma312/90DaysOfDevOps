# Day 23 Task: Jenkins Freestyle Project(Docker project from Day19 used)

### Task-1 

- Create a new Jenkins freestyle project for your app.

  [![HvU3kTQ.md.png](https://iili.io/HvU3kTQ.md.png)](https://freeimage.host/i/HvU3kTQ)
  
  [![HvU38ZB.md.png](https://iili.io/HvU38ZB.md.png)](https://freeimage.host/i/HvU38ZB)
  
  [![HvU3r6F.md.png](https://iili.io/HvU3r6F.md.png)](https://freeimage.host/i/HvU3r6F)


- In the "Build Steps" section of the project, add a build step to run the "docker build" command to build the image for the container.

  [![HvUFoFe.md.png](https://iili.io/HvUFoFe.md.png)](https://freeimage.host/i/HvUFoFe)
  
  [![HvUFT9j.md.png](https://iili.io/HvUFT9j.md.png)](https://freeimage.host/i/HvUFT9j)


- Add a second step to run the "docker run" command to start a container using the image created in step 3.

  [![HvUFRtV.md.png](https://iili.io/HvUFRtV.md.png)](https://freeimage.host/i/HvUFRtV)
  
  [![HvUFlKF.md.png](https://iili.io/HvUFlKF.md.png)](https://freeimage.host/i/HvUFlKF)
  
- Project running.

  [![HvUKRJs.md.png](https://iili.io/HvUKRJs.md.png)](https://freeimage.host/i/HvUKRJs)


### Task-2

- Create Jenkins project to run "docker-compose up -d" command to start the multiple containers defined in the compose file.

  [![HvUKczl.md.png](https://iili.io/HvUKczl.md.png)](https://freeimage.host/i/HvUKczl)
  
  [![HvUKEq7.md.png](https://iili.io/HvUKEq7.md.png)](https://freeimage.host/i/HvUKEq7)

- Set up a cleanup step in the Jenkins project to run "docker-compose down" command to stop and remove the containers defined in the compose file.

  [![HvUKhej.md.png](https://iili.io/HvUKhej.md.png)](https://freeimage.host/i/HvUKhej)
  
  [![HvUKOXV.md.png](https://iili.io/HvUKOXV.md.png)](https://freeimage.host/i/HvUKOXV)
  
  
