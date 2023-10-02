# Badge status
[!CircleCI](https://dl.circleci.com/status-badge/img/gh/trungld123/trungld6_project5/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/img/gh/trungld123/trungld6_project5/tree/main.svg?style=svg)

# Url app
http://a798d3777b450463dae2ad6349dfc917-1202729838.us-east-1.elb.amazonaws.com:3000/
# Github
https://github.com/trungld123/trungld6_project5

# CircleCi
https://app.circleci.com/pipelines/github/trungld123/trungld6_project5?branch=main

# Propose and Scope the Project
1. My pipeline
    | Build --> Push --> Deploy
2. Use Circle CI for Continuous Integration phase.
3. Deployment type: blue/green deployment.
4. Application: nodejs sample application

# Pick AWS Kubernetes as a Service.
1. ```eksctl``` 
2. ```kubectl``` 

# Build pipeline
1. Steps in CircileCI: 
    - build: Build app and lint Dockerfile
    - push: Build and push docker image
    - deploy: Deploy and expose app to AWS EKS
2. Configure a deployment pipeline
    - ```.circleci/config.yml```
3. Dockerfile
    - ```./backend/Dockerfile```
