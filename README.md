This project implements a complete end-to-end CI/CD pipeline using Terraform, Jenkins, Docker, and Kubernetes (EKS).

Project Architecture
Tools & Technologies Used
Cloud Infrastructure: AWS (VPC, EKS, EC2)
Infrastructure as Code (IaC): Terraform
CI/CD Automation: Jenkins
Containerization: Docker & Nginx
Orchestration: Kubernetes (EKS)
Monitoring: Prometheus & Grafana
Key Objectives Accomplished
Automated Provisioning: Terraform was used to provision a secure VPC, Jenkins build server, and EKS cluster.
CI/CD Pipeline: A Jenkins declarative pipeline was configured to trigger on GitHub pushes, build Docker images, and deploy them to Kubernetes.
Scalability: Kubernetes deployments were implemented with multiple replicas and LoadBalancer services to ensure high availability.
Observability: Prometheus and Grafana were integrated to provide real-time monitoring of cluster and application performance.
