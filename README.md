# Provision a K8s application

Terraform configuration files to provision a K8s deployment and service on AWS EKS cluster.

## The code creates:
1. K8s deployment - replicas=2 image=ranra96/bp_nginx_ran:latest
2. K8s service (LB)

## Requierments
1. AWS EKS Cluster
2. a configured AWS CLI
