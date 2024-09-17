# K8s Deploy Nita

## Description
This project contains Kubernetes configurations for deploying a web application using Nginx and MySQL.

## Getting Started

### Prerequisites
- Minikube installed on your local machine.
- kubectl installed on your local machine.
- Docker installed on your local machine.

### Running the Application
1. Clone this repository:
   git clone https://github.com/nsasli/k8s-deploy-nita.git
   cd k8s-deploy-nita

2. Start Minikube: minikube start
3. Apply the Kubernetes configurations:
4. Access the application


Technologies Used
1. Kubernetes
2. Minikube
3. Docker
4. Prometheus
5. Grafana
6. CI/CD Pipeline

This project uses GitHub Actions for CI/CD. The pipeline is set up to:

Automatically build and test the application on push.
Deploy changes to the Kubernetes cluster.
Monitoring
Prometheus is used for monitoring the application's performance and Grafana is used for visualizing the metrics.

Authors
Nita S
