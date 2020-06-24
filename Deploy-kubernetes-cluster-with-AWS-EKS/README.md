# Deploy Kubernetes cluster with AWS EKS


## Use case:
We have a containerized application and want to deploy it onto Kubernetes cluster managed by Amazon Elastic Container Service for Kubernetes (Amazon EKS).


## Pre-requisites:
Before starting create cluster, we have to make sure that the following components are installed and set up.
-	AWSCLI (AWS Console to create a cluster in EKS)
-	Kubectl (Required for communicating with the cluster API server)


## Steps to create cluster and integrate with worker nodes in EKS:

**Step#1:** Create an EKS Role using IAM Console

**Step#2:** Create a VPC for EKS using CloudFormation Console

**Step#3:** Create an EKS Cluster using AWSCLI

**Step#4:** Update kubeconfig to communicate with new cluster

**Step#5:** Create Kubernetes worker nodes using CloudFormation Console

**Step#6:** Allow worker nodes to join with Kubernetes cluster

**Step#7:** Deploy application on Kubernetes


## Consume Amazon web services:
These AWS Services are being used in this approach.
-	EKS
-	IAM
-	CloudFormation
-	EC2
-	Security Group
-	Load Balancer


## Application Architecture:
 ![Architecture of AWS EKS](Deploy_Kubernetes_cluster_with_AWS_EKS.png)
 
 
## Benefits:
-	Speed up delivery while improving quality
-	Scaling containerized applications
-	Automates load distribution
-	High Availability
