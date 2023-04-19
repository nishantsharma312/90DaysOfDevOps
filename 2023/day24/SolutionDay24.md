# Day 24 Task: Jenkins Project Deployment

- Fork [this](https://github.com/LondheShubham153/node-todo-cicd.git) repository.

- Create a Jenkins freestyle job.

  ![1](https://user-images.githubusercontent.com/77112379/233140031-55b33907-3449-41d2-ab97-a19d0ab15d0f.png)

  ![2](https://user-images.githubusercontent.com/77112379/233140207-31e83e40-7fbc-4466-8a6f-6becc2a8f05a.png)

  ![3](https://user-images.githubusercontent.com/77112379/233140228-fbe1a179-193a-4d03-b4b9-7c1d41efe912.png)
  
- Use Gitscm polling to connect GitHub repo with Jenkins.

  ![4](https://user-images.githubusercontent.com/77112379/233140624-33c211e2-6a9c-4282-8acc-5795778ad7e4.png)

- Configure GitHub Webhooks in repository settings.

  ![5](https://user-images.githubusercontent.com/77112379/233140966-318d41d8-0f46-4107-97a1-96f3a3e37851.png)
  
  ![6](https://user-images.githubusercontent.com/77112379/233141083-fcafee74-9743-47e5-8e83-e2d4f6693a5b.png)
  
- Add build steps in Execute shell.

  ![7](https://user-images.githubusercontent.com/77112379/233141328-2439afce-6970-41f1-beb0-c0fd412670b6.png)

- We are done! Now if any change is committed in our repository our project will be automatically updated. No need to manually run **build now** option as we did in delivery tasks on day23.

  ![8](https://user-images.githubusercontent.com/77112379/233142792-544f9fed-b166-41d9-a63f-06578871dbd4.png)

- Checking the deployed project.
  
  ![9](https://user-images.githubusercontent.com/77112379/233142799-4df0c850-7f77-4bdf-93f5-c914f425a589.png)


