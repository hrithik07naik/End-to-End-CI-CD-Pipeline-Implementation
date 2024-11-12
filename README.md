# N-Tier Architecture Microservices CI/CD Pipeline

## Project Overview
This project demonstrates an end-to-end CI/CD pipeline for an N-Tier microservices application. The application comprises three microservices developed in Python, .NET, and Java, with a Redis cache and a MySQL database for storing user information.

- **CI/CD Pipeline**: Built using Azure DevOps, deploying to AKS via Argo CD and Ansible.
- **Technologies**: AKS, Argo CD, Ansible, Redis, MySQL, Docker, GitOps.
- **Architecture**: Multi-language microservices with caching and persistent storage.

## Repository Contents
- **Pipelines**: YAML files defining CI pipelines for each service.
- **Infrastructure as Code (IaC)**: Terraform scripts to provision AKS and MySQL resources.
- **Deployment Configuration**: Kubernetes manifests, Helm charts, and Argo CD configuration.
