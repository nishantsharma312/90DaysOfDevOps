# Day 35: ConfigMaps and Secrets in Kubernetes

- Create a new namespace for mysql add this namespace in all the manifest files.
  
  `kubectl create namespace mysql-db`
  
- Create a ConfigMap manifest file.
  
  ![configmap](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/831b752c-f0f5-4b76-9034-f5f79f5c5d8e)
 
- Encode your password for secret manifest file using command

  `echo 'your password' | base64`
  
- Create a secret manifest file.
  
  ![secret](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/f25cdcf6-3762-4012-bcaa-7e2527779a5c)

- Create a deployment manifest file for mysql and add configmap and secret in it.
  
  ![deployment1](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/b8f9fd61-7d07-4575-a1d6-2bcb5f27ef24)
  ![deployment2](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/fbe15f56-7a4f-4793-8463-bc3118314568)

- Verify that the ConfigMap has been created by checking the status of the ConfigMaps in your Namespace.
  
  ![Screenshot from 2023-05-16 23-29-01](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/fb8ac0aa-a8fd-4078-9a80-97dabafc5c83)

- Verify that the Secret has been created by checking the status of the Secrets in your Namespace.

  ![Screenshot from 2023-05-16 23-29-28](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/cf20a9a2-3869-4452-bbfe-9ea43d1efa41)
  ![Screenshot from 2023-05-16 23-30-03](https://github.com/nishantsharma312/90DaysOfDevOps/assets/77112379/5f2599bd-da99-4466-8c61-3eebaa89d542)
