K8s Deploy Nita
Description
This project contains Kubernetes configurations for deploying a web application using Nginx and MySQL.

Getting Started
Prerequisites
Minikube installed on your local machine.
kubectl installed on your local machine.
Docker installed on your local machine.
Running the Application
Clone this repository: git clone https://github.com/nsasli/k8s-deploy-nita.git cd k8s-deploy-nita

Start Minikube: minikube start

Apply the Kubernetes configurations:

Access the application

Technologies Used

Kubernetes
Minikube
Docker
Prometheus
Grafana
CI/CD Pipeline
This project uses GitHub Actions for CI/CD. The pipeline is set up to:

Automatically build and test the application on push. Deploy changes to the Kubernetes cluster. Monitoring Prometheus is used for monitoring the application's performance and Grafana is used for visualizing the metrics.

Authors 
Nita S
