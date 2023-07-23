# Project description
This project is for the final capstone project of Udacity Cloud DevOps Engineer course. This project will be made for AWS.
The project includes:
- Implement CI/CD pipelines using CircleCI.
- Using CloudFormation to create EC2 Kubernetes cluster.
- Deploy Application using Docker.
- Deploy container using Kubernetes.

# Application
The application is a simple webpage, based on python3 script and rendered by flask.

# Kubernetes hosts
- The Kubernetes host will be created using CloudFormation script.
- Kubernetes host will be EC2 instance, with additional setup.

# CI/CD Pipelines
The pipelines is built using CircleCI.
Ansible is used to:
- Configure the cluster: install all required dependencies.
- Deploy app: 
    - Start local kubernetes.
    - Deploy application using docker image.
    - Port-forward the pod.

