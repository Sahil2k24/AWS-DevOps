# Setting up Amazon EKS with eksctl

## Introduction
Excited to share my latest experience with Amazon EKS (Elastic Kubernetes Service) and how I set up my first EKS cluster using eksctl!

## Steps I Took

### Installed eksctl on PowerShell
The eksctl CLI tool makes creating and managing Kubernetes clusters on EKS a breeze.

### Installed and Configured AWS CLI
Set up the AWS CLI to interact with AWS services programmatically.

### Configured AWS
Properly configured AWS credentials and region settings.

## Creating the Cluster

### Outcome
Successfully created an EKS cluster named devops-cluster with 2 nodes and a VPC with 4 subnets.

### Region Challenges
Initially tried to create the cluster in the us-east-1 (N. Virginia) region, but encountered an issue with the availability zone us-east-1e.
Resolved by switching to the us-west-1 (N. California) region, where the cluster was created successfully.

### Time Taken
Approximately 10 minutes to get the cluster up and running.

## Key Learnings

- Be mindful of the availability zones when creating resources.
- Having alternative regions in mind can save time and effort.

## Conclusion
Super thrilled to have this hands-on experience with EKS and eksctl! Looking forward to leveraging this for future Kubernetes projects. 🚀

## Tags
#AWS #EKS #Kubernetes #DevOps #CloudComputing #AWSCLI #eksctl #CloudNative #InfrastructureAsCode
