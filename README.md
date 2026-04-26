# AKS Helm Demo

This repo contains:
- Node.js app
- Dockerfile
- Helm chart
- Terraform configs
- Azure DevOps pipelines

## Usage
- terraform init && terraform apply
- helm install aks-helm-demo ./helm
- CI/CD pipelines build/push images and deploy to AKS
