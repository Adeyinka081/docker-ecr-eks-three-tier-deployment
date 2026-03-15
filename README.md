# Docker → ECR → EKS Three-Tier Deployment

This project demonstrates how to deploy a containerized web application on AWS using Kubernetes.

## Architecture

Docker → Amazon ECR → Amazon EKS → Kubernetes → LoadBalancer → Public Website

## Project Overview

In this project I:

1. Created a Docker image for a simple web application
2. Pushed the image to Amazon ECR
3. Created an Amazon EKS cluster
4. Deployed the application using Kubernetes
5. Exposed the application with an AWS LoadBalancer
6. Accessed the application through a public URL

## Tools Used

- Docker
- AWS ECR
- AWS EKS
- Kubernetes (kubectl)
- Helm
- AWS CLI

## Deployment Steps

### Build Docker Image

```bash
docker build -t three-tier-app .
