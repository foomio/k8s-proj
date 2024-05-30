# Kubernetes Project 1 -  Minikube Deployment 

## Details
Make sure you have minikube installed and Docker open!! 

In this project, I have set up a Kubernetes cluster with minikube.

First you mustart the service with 
```
minikube start
```
this may take a few minutes

Then I created a deployemnt.yaml and service.yaml file and applied them with the following command
```
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```