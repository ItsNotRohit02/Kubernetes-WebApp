# Kubernetes-Based Multi-Tier Web Application Deployment on AWS

## Project Overview

This project involves setting up and deploying a multi-component web application on AWS using Kubernetes. The deployment is designed to ensure scalability, security, and high availability for a web application consisting of a MySQL database, Memcached, RabbitMQ, and the web application itself.

## Key Features

- **Kubernetes Cluster Setup:** Configured a Kubernetes cluster on AWS using kops.
- **Docker Images:** Created and managed Docker images for various application components.
- **Service Deployment:** Deployed multiple services including MySQL, Memcached, RabbitMQ, and a web application.
- **Persistent Storage:** Configured AWS EBS volumes for persistent storage.
- **Kubernetes Secrets:** Managed sensitive information securely with Kubernetes Secrets.
- **Init Containers:** Used init containers to manage service dependencies and ensure proper initialization order.
- **LoadBalancer Service:** Exposed the web application using a LoadBalancer service for external access.

## Technologies Used

- **Kubernetes**
- **Docker**
- **AWS (EBS, LoadBalancer)**
- **kops**
- **MySQL**
- **Memcached**
- **RabbitMQ**
- **Tomcat**
