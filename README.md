# End-to-End CI/CD Pipeline for N-Tier Architecture Microservices

## Project Overview
This project demonstrates the implementation of an end-to-end CI/CD pipeline for an N-Tier microservices application. The application consists of three microservices developed in Python, .NET, and Java. It uses Redis for caching and MySQL for storing user data.

### Key Features:
- **CI/CD Pipeline**: Automated deployment using Azure DevOps pipelines and GitOps through Argo CD.
- **Technologies**: Azure Kubernetes Service (AKS), Argo CD, Ansible, Redis, MySQL, Docker, GitOps.
- **Architecture**: Multi-language microservices with caching and persistent storage.

## Repository Structure
- **CI Pipelines**: YAML files for defining CI/CD pipelines for each service.
- **Infrastructure as Code (IaC)**: Terraform configurations to provision Azure resources (AKS, MySQL).
- **Kubernetes Manifests**: Deployment files for Kubernetes, including Helm charts and Argo CD configuration.
- **Ansible Playbooks**: Automation scripts for deploying microservices to AKS.
- **Dockerfiles**: Containerization configurations for each microservice.

## Technologies Used:
- **Programming Languages**: Python, .NET, Java
- **CI/CD Tooling**: Azure DevOps, Argo CD
- **Infrastructure**: Terraform, Kubernetes, Helm
- **Caching**: Redis
- **Database**: MySQL

## Setup Instructions:
1. Clone the repository.
2. Set up your Azure account and configure Terraform for AKS and MySQL provisioning.
3. Follow the pipeline setup instructions in `ci-pipelines/` to configure Azure DevOps pipelines.
4. Use Ansible for deploying the services on AKS.
5. Apply Kubernetes manifests via Argo CD.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, reach out to hrithiknaik2001@gmail.com.
