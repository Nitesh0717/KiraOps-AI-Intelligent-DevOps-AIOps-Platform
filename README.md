# KiraOps-AI-Intelligent-DevOps-AIOps-Platform

# KiraOps-AI — Intelligent DevOps & AIOps Platform

A full end-to-end DevOps project with AIOps integration — connecting the dots between modern cloud operations, continuous delivery, and artificial intelligence.

---

## Welcome

Welcome to **KiraOps AI**! This project demonstrates how modern cloud infrastructure, Kubernetes orchestration, GitOps automation, and Generative AI (AWS Bedrock) work together in a production-grade DevOps environment.

In this project:
* Build microservices locally with Docker & Docker Compose
* Use Claude Code and MCP tools to assist cloud management
* Deploy infrastructure step-by-step using Terraform
* Migrate and manage systems on AWS EKS
* Set up CI/CD pipelines with GitHub Actions
* Implement GitOps continuous delivery with ArgoCD & Kustomize
* Integrate AIOps log analysis and anomaly detection with AWS Bedrock (Agent Kira)

---

## Repository Structure

```text
KiraOps-AI-Intelligent-DevOps-AIOps-Platform/
├── docs/
│   ├── part1-system-design.md     # System design foundations
│   ├── part2-workflow.md          # Full workflow with AIOps
│   └── claude-setup.md            # Claude Code + MCP server setup
├── projects/
│   ├── README.md                  # EKS deployment guide
│   ├── boutique-microservices/    # Microservices application
│   ├── Infrastructure/            # Terraform for AWS provisioning
│   └── aiops-assistant/           # Bedrock Agent — Kira
├── gitops/
│   ├── argo-cd.yml                # ArgoCD Application manifest
│   ├── kustomization.yml          # Kustomize entry point
│   └── k8s/                       # All Kubernetes manifests
└── .github/
    └── workflows/ci.yml           # GitHub Actions CI pipeline
