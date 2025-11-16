# Homelab K3s Cluster

This repository houses all configuration and declarative files for a **homelab K3s cluster**, demonstrating **GitOps, CI/CD, Infrastructure as Code (IaC), and Configuration as Code (CaC) practices**. It serves as a showcase of practical Kubernetes skills on small-scale hardware for educational and professional purposes.

## Cluster Overview

- **Master Node:** Raspberry Pi 4 running Raspberry Pi OS Lite
- **Worker Node:** Raspberry Pi 3B+ running Raspberry Pi OS Lite
- **Kubernetes Distribution:** [K3s](https://k3s.io/) (lightweight, production-ready)  
- **Purpose:** Learning, experimentation, and demonstration of DevOps best practices

### Architecture Diagram


## Features

- **Infrastructure as Code (IaC):** Scripts to bootstrap the cluster and configure nodes.  
- **Configuration as Code (CaC):** Declarative Kubernetes manifests and Helm charts.  
- **GitOps:** Optionally deploy applications using ArgoCD or Flux for automated cluster reconciliation.  
- **CI/CD:** GitHub Actions workflows for validating manifests, running tests, and deploying to the cluster.  
- **Observability:** Placeholders for monitoring (Prometheus, Grafana) and logging pipelines.

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/<your-username>/k3s-cluster.git
cd k3s-cluster

