# Day 32 Task: Launching your Kubernetes Cluster with Deployment

## Task : Create one Deployment file to deploy a sample todo-app on K8s(kubeadm used) cluster
- Create pod.yml file for application.

  ![pod](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/2f18398e-8fee-43b3-bb2c-b984b42b814a)

- Run the deployment file using the command on master.
  `kubectl apply -f deployment.yml`
  
  ![Pod](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/6a37e2b9-db2b-4527-92c1-9d59c8c9e9ff)

- Write the deployment file for the application.

  ![deployment](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/633c9ccb-23fa-42a2-8e95-ff5175055dd8)

- Run the deployment file using the command on master.
  `kubectl apply -f deployment.yml`
  
- Now, check if the deployment is running using command.`kubectl get deployments -n=<namespace>`

- List the pods using command `kubectl get pods -n=<namespace>` and verify number of pod replicas.
  
  ![Deployment](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/890b6a2b-332a-434d-a825-43b7d21714ca)

- We can also verify containers in worker node using `docker ps` command.
  
  ![dockerps](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/b928ae0c-3a48-4a4f-ac44-14f498efbf25)
  

  
