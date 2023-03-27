# Day 7 Task: Understanding package manager and systemctl

## Tasks
1) You have to install docker and jenkins in your system from your terminal using package managers. 
   Write a small blog or article to install these tools using package    managers.

   Link to the Blog - https://nishantsharma.hashnode.dev/guide-to-install-docker-and-jenkins-on-aws-ec2-instance
   
   
   ![Q1 b](https://user-images.githubusercontent.com/77112379/228039222-576ef822-2f6d-4cbc-b892-b333822afb0b.jpg)

   
   ![jenkins status](https://user-images.githubusercontent.com/77112379/228039322-0473693d-e542-4bdf-9785-2b37ed2de12c.jpg)

  
2) Check the status of docker service in your system.

   ![Screenshot 2023-03-28 001136](https://user-images.githubusercontent.com/77112379/228039900-0f394daa-a563-45b4-a769-411ca45fc019.jpg)
  

3) Stop the service jenkins and post before and after screenshots.

   Before : 
   
   ![Screenshot 2023-03-28 001245](https://user-images.githubusercontent.com/77112379/228040150-1d436aab-b85e-4c8a-9136-79c816f0007e.jpg)

   After :
   
   ![Screenshot 2023-03-28 001344](https://user-images.githubusercontent.com/77112379/228040189-f02d2de5-0e15-40fc-9a07-1ca8d9790add.jpg)

4)  systemctl vs service

    systemctl is basically a more powerful version of service. With service you can only do commands related to the 
    service (i.e. status, reload, restart) whereas with systemctl you can use more advanced commands such as:
    (systemctl is-failed name.service # check if service failed to load).
   
