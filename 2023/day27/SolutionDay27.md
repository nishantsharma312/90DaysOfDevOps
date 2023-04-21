#  Day 27 : Jenkins Declarative Pipeline with Docker

## Task 1 Using 'sh' syntax

- Create a new declarative pipeline.

  ![1](https://user-images.githubusercontent.com/77112379/233655245-35f138b6-662e-4790-8502-9f7159502e15.png)

- Give Description.
  
  ![2](https://user-images.githubusercontent.com/77112379/233655363-a093c306-ef52-4661-a500-f7987358f88a.png)

- Configure the pipeline by writing the groovy script for the app.
  
  ![3](https://user-images.githubusercontent.com/77112379/233655446-1553686c-24eb-4704-812f-bab51beab18f.png)

- Build now. Pipeline running.
  
  ![4](https://user-images.githubusercontent.com/77112379/233655548-6abfa944-79df-42a1-afe3-9b7cb35b1fb3.png)

- Console output.

  ![5](https://user-images.githubusercontent.com/77112379/233655599-2a590d72-5d0b-48a7-8203-018e3442335e.png)

- Checking if app is live.
  
  ![6](https://user-images.githubusercontent.com/77112379/233655682-a1f50091-88ff-47b4-94a4-832a91e19dcd.png)
  
- But if we build the app again we get errors.

  ![7](https://user-images.githubusercontent.com/77112379/233655751-3f92f916-d535-4bbb-90a5-1a494f1491d1.png)


# # Task 2 Using 'docker' groovy syntax

- Edit the script with groovy syntax.
  
  ![8](https://user-images.githubusercontent.com/77112379/233658696-6d24a0d0-f58e-413c-9951-e662ede2cacc.png)

- Stage view.(no errors)

  ![9](https://user-images.githubusercontent.com/77112379/233658704-c54ef181-8100-479a-9b0f-7961c7b9fd26.png)

- Console output.

  ![10](https://user-images.githubusercontent.com/77112379/233655886-e5a8935b-1e36-4926-8163-0c13741f90d9.png)

- App is live.

  ![11](https://user-images.githubusercontent.com/77112379/233655934-55440bf9-a37d-48c9-849b-b330ac04436f.png)

- **Note** : if u are getting error like this `workflowscript: 11: invalid agent type "docker" specified. must be one of [any, label, none] @ line 11, column 17. docker{
error!!!` install docker plugins in Jenkins (Dashboard >> Manage Jenkins >> Available Plugins >> Download Docker Pipeline and Docker Plugins).
