
# Hackerbay Server Monitoring Project - Kubernetes Configurations

This is the "Kubernetes Configurations" for Server Monitoring Project. 
  - FrontEnd part of the project can be found on [Hackerbay - Frontend.](https://github.com/SandunWebDev/hackerbay-frontend/)
  - Backend part of the project can be found on [Hackerbay - Backend.](https://github.com/SandunWebDev/hackerbay/)


## How To Run

  - First create file called "backend-secrets.yml" with necessary values. (Template can be found on "template.backend-secrets.yml")
  - Then just run 
  
    `kubectl apply -f backend-secrets.yml -f database.yml -f backend.yml -f frontend.yml`

  - If deployed in minkube cluster use `minkube service list` to find out external IPs to services.
    If deployed in cloud service cluster like Google Kubernetes Engine use `kubectl get service` to find out external IPs to services.

  - To inspect if all the items running correctly use `kubectl get all` and `kubectl describe all`.
     
