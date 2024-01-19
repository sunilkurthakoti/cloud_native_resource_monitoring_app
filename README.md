
# Cloud Native Resource Monitoring App

This project focuses on creating a simple DevOps application using Python, Flask, and psutil to monitor system resources. The deployment is orchestrated using Kubernetes.

## Steps to Create and Deploy the Monitoring App: 
### 1. Creating a Python Monitoring App:
A Python app is developed using Flask and psutil to monitor system resources. The application provides a straightforward interface to track essential metrics.

### 2. Dockerizing the App:
A Dockerfile is written to containerize the Python monitoring app. A Docker image is built, and Docker containers are run to ensure consistency across different environments.

### 3. ECR Repository Creation and Image Push:
Using Python boto3, an Amazon Elastic Container Registry (ECR) repository is created. The Docker image of the monitoring app is pushed to this repository, making it accessible for deployment.

### 4. AWS EKS Cluster Setup:
An Amazon EKS cluster is established, and a node group is configured to manage the computing resources. This sets the stage for deploying and scaling the monitoring app seamlessly.<br>

### 5. Deploying the Monitoring App on Kubernetes:
The Docker image from the ECR repository is deployed onto the AWS EKS cluster. Kubernetes orchestrates the deployment, ensuring scalability, reliability, and efficient resource utilization.



## Creating an python monitoring app using flask and psutil

![Screenshot (155)](https://github.com/sunilkurthakoti/cloud_native_resource_monitoring_app/assets/131526336/b8090dbf-8790-4876-878a-bbf7e8935194)

<br>

## Creating an ECR repository and pushing the Docker image to the repository

![Screenshot (161)](https://github.com/sunilkurthakoti/cloud_native_resource_monitoring_app/assets/131526336/8f8d7f6c-ad9e-4314-a6c9-5b8068c72994)

<br>

## Creating an EKS cluster and Deploying it on Kubernetes

![Screenshot (163)](https://github.com/sunilkurthakoti/cloud_native_resource_monitoring_app/assets/131526336/8310e063-cf57-456e-bf42-2ab7a843634b)

<br>

## Feedback

If you have any feedback, please reach out to us at sunilkurthakoti06@gmail.com

