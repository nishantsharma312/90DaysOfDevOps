# Day 34 Task: Working with Services in Kubernetes

## Task-1
- Create a Service definition for your todo-app Deployment in a YAML file.
  
  ![1](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/c1fdd6df-c1c7-42bc-9ace-0cb9aae637fb)

- Apply the Service definition to your K8s cluster using the `kubectl apply -f service.yml -n <namespace-name>` command.
  
  ![2](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/96d042bc-9f11-4e53-9bfd-b03b2cdf4a6b)

- Verify that the Service is working by accessing the todo-app.(dont forget to add port in security group/inbound rules)
  
  ![3](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/cf0aab64-c7b9-489f-a9ad-ab684ef1aa64)

## Task-2
- Create a ClusterIP Service for accessing the todo-app from within the cluster.
  Create a ClusterIP Service definition for your todo-app Deployment in a YAML file.
  
  ![4](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/da2de48b-8cb3-416e-a1da-ea12bcf9faa8)

- Apply the ClusterIP Service
  
  ![5](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/2f28bc3e-aa92-485d-b900-1f8b55bf929f)

- Verify that the ClusterIP Service is working
  
  ![6](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/579282c2-e2fd-42a1-8823-cc60694d8fdc)

## Task-3
- Create a LoadBalancer Service for accessing the todo-app from outside the cluster
  Create a LoadBalancer Service definition for your todo-app Deployment in a YAML file.
  
  ![7](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/091e2fcd-0ba4-4a97-b748-de0b8988d8ab)

- Apply the LoadBalancer Service
  
  ![8](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/76837a68-ac20-421c-a1de-d17a0f0fdaab)

- Verify that the LoadBalancer Service is working by accessing the todo-app from outside the cluster in your Namespace.(Using Public ipv4 DNS : port number to verify)
  
  ![9](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/46fa79aa-b583-437b-be9f-6079776003bf)

  
