# KiraOps AI — Claude Instructions

## Critical Safety Directive
Explain what you're about to do and why BEFORE taking any action.
Never execute destructive commands (e.g. deleting EKS clusters, terminating instances, wiping databases) without explicit confirmation.

## Project Overview
This repository hosts KiraOps AI — an intelligent end-to-end DevOps & AIOps Platform.
It integrates microservices containerization, Terraform IaC, EKS Kubernetes deployment, ArgoCD GitOps, and AWS Bedrock AIOps assistants.

## Useful Commands
- Infrastructure: `cd projects/Infrastructure && terraform plan`
- Local Stack: `docker compose up -d`
- Kubernetes: `kubectl get pods -n kiraops`
- CI Pipeline: GitHub Actions triggered on push to main branch

