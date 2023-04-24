# Day 28 Task: Jenkins Agents

## Pre-requisites

- Create 2 instances master and agent

  ![1](https://user-images.githubusercontent.com/77112379/233949224-0366e1db-ed22-4704-ba67-cc32d08ba300.png)  

- install java on both
- install jenkins on master
- install docker on agent

# Task-01

- Generate SSH keys on “Jenkins-master” EC2 instance

  ![2](https://user-images.githubusercontent.com/77112379/233949608-30b8aee3-fbd9-4943-983a-e5284fe905ef.png)
  
- Copy id_rsa.pub (public key) to agent .ssh/authorized_keys

  ![3](https://user-images.githubusercontent.com/77112379/233950198-40689c9d-f953-485f-ac35-24b1c3cbfb2d.png)

  ![4](https://user-images.githubusercontent.com/77112379/233950207-5678305e-1115-4559-94c0-e216351e9932.png)

- Create an agent by setting up a node on Jenkins

  ![5](https://user-images.githubusercontent.com/77112379/233951189-4a77d577-8982-4058-ae72-9c6458c281cd.png)

  ![6](https://user-images.githubusercontent.com/77112379/233951208-74bbc812-cd80-4fb3-9047-f4101665b8a4.png)

  ![7](https://user-images.githubusercontent.com/77112379/233951242-35c5ed23-00f1-4866-8c12-95b274caac0e.png)
  
  ![8](https://user-images.githubusercontent.com/77112379/233951255-c3b8a289-ad9a-4328-aa5a-1aa26ab3d297.png)
  
  ![9](https://user-images.githubusercontent.com/77112379/233951269-c0c70851-d2ff-4677-b2dd-43e1c3224e20.png)
  
- Add private key that we created in 'jenkins-master' instance.

  ![10](https://user-images.githubusercontent.com/77112379/233951584-0132f77d-5654-491e-a5e9-6e8244258ac6.png)
  
  ![11](https://user-images.githubusercontent.com/77112379/233951606-ae742e80-7b07-4c0a-8d4e-98362c46b339.png)

  ![12](https://user-images.githubusercontent.com/77112379/233951625-cdf0a552-18dc-4fab-a624-b64e415ecd70.png)
  
- Click on save to create node. You can see agent will be connected and online.
  
  ![13](https://user-images.githubusercontent.com/77112379/233952234-5e411721-de9f-4e58-ba8c-f399f64f5da8.png)
  
  ![14](https://user-images.githubusercontent.com/77112379/233952255-19f91649-d430-450c-afee-a8222c918631.png)

# Task-02

- if you have a freestyle project edit configuration to add agent.

  ![15](https://user-images.githubusercontent.com/77112379/233953299-83da4189-c536-4cd2-b11e-a3e989055492.png)

- if you have a pipeline add agent in groovy script.
  
  ![16](https://user-images.githubusercontent.com/77112379/233953318-3793de8a-352a-424b-a42f-1b3e54609298.png)

- We can see in console output that project is running on Agent1.
  
  ![17](https://user-images.githubusercontent.com/77112379/233953329-6a111360-c3ac-4aaf-83c9-04e59ac127c5.png)

