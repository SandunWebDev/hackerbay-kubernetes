
# Hackerbay Server Monitoring Project - Kubernetes Configurations

This is the "Kubernetes Configurations" for Server Monitoring Project. 
  - FrontEnd part of the project can be found on [Hackerbay - Frontend.](https://github.com/SandunWebDev/hackerbay-frontend/)
  - Backend part of the project can be found on [Hackerbay - Backend.](https://github.com/SandunWebDev/hackerbay/)


## How To Run

  - First create "backend-secrets.yml" file with necessary values. (Template can be found on "template.backend-secrets.yml")
  - Then just run 
  
    `kubectl apply -f backend-secrets.yml -f database.yml -f backend.yml -f frontend.yml`