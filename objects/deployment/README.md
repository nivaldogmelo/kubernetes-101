# Deployments
Deployment is an object which you can use to configure your applications, in the deployment yaml you can set things like the containers you're gonna deploy, how many replicas, environment variables that will be used, persistent volumes and so on. It's a combination of two other objects of Kubernetes, Pod and Replication Controller.

## Pod
It is the smallest deployable unit you can manage in Kubernetes, it can contain one or more containers. Each pod gets a unique IP address, and containers in the same pod shares the network namespace, they can communicate themselves with localhost

## ReplicaSet
It is a service responsible for manage how many replicas of a pod will be deployed at the cluster

## Deployment Features
In a deployment you can configure a series of features that will help you manage your application, that includes...
