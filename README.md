## Kubernetes based Continuous Delivery

### Objectives

1) Create a customized Docker container from the current version of Python that deploys a simple python script.
2) Push image to DockerHub, or Cloud based Container Registery (ECR)
3) Project should deploy automatically to Kubernetes cluster
4) Deployment should be to some form of Kubernetes service (can be hosted like Google Cloud Run or Amazon EKS, etc)

### Implemetation
#### Pushing image to ECR
1) Git clone repository on aws cloud9 environment
2) create python virtual environment
3) Create "Dokerfile" 
4) Now switch to ECS
5) Create a repository for your image in ECR
6) Checkout instructions for building, tagging and pushing image to ECR.
7) Copy and paste and run instructions into cloud9
8) Image should be successfully added to ECR repository created

#### Deploying image through Fagate and Amazon Elastic Kubernetes services (EKS)
1) Create clusters
2) Create load balancer
3) Create target group
4) Link target group to load balancer
5) Edit security group for external access
6) Access BMI calculator through FASTAPI Swagger UI : http://bmi-load-balance-903337452.us-east-1.elb.amazonaws.com/docs#/default/bmi_calculator_bmi_calculator__weight___height__get



Reference Reading: https://learning.oreilly.com/library/view/python-for-devops/9781492057680/ch09.html#containers-docker

Reference Source Code: https://github.com/noahgift/container-revolution-devops-microservices
