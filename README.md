This project implements a complete end-to-end CI/CD pipeline using Terraform, Jenkins, Docker, and Kubernetes (EKS).

Project Architecture

Tools & Technologies Used
•	Cloud Infrastructure: AWS (VPC, EKS, EC2) 
•	Infrastructure as Code (IaC): Terraform 
•	CI/CD Automation: Jenkins 
•	Containerization: Docker & Nginx 
•	Orchestration: Kubernetes (EKS) 
•	Monitoring: Prometheus & Grafana 

Key Objectives Accomplished

•	Automated Provisioning: Terraform was used to provision a secure VPC, Jenkins build server, and EKS cluster. 
•	CI/CD Pipeline: A Jenkins declarative pipeline was configured to trigger on GitHub pushes, build Docker images, and deploy them to Kubernetes. 
•	Scalability: Kubernetes deployments were implemented with multiple replicas and LoadBalancer services to ensure high availability. 
•	Observability: Prometheus and Grafana were integrated to provide real-time monitoring of cluster and application performance

Project Screenshots :

1.Terraform configurations
<img width="950" height="510" alt="tf plan 3" src="https://github.com/user-attachments/assets/dd1b83a8-7fc5-4860-bdc8-6fa9f01d3630" />
<img width="955" height="512" alt="TF init" src="https://github.com/user-attachments/assets/932d55fa-2bed-4892-b23d-6c59c1bf25e2" />
<img width="952" height="506" alt="tf apply final ss" src="https://github.com/user-attachments/assets/b423c446-ad71-4dfb-a161-0be5c07c81e9" />

2.Jenkins Pipelines
<img width="947" height="509" alt="jenkins pipeline name" src="https://github.com/user-attachments/assets/a9936b78-2394-46f5-afc3-324166c00716" />
<img width="950" height="509" alt="Jenkins pipeline ss1" src="https://github.com/user-attachments/assets/e8c2f6e9-0ee4-4a13-a0c7-5bd53c21953e" />
<img width="950" height="514" alt="jenkins pipeline ss2" src="https://github.com/user-attachments/assets/332ec6af-6061-4b41-ab4c-4b4d8875ccad" />
<img width="941" height="506" alt="Jenkins pipeline cmplt ss" src="https://github.com/user-attachments/assets/e68922c6-2911-4da1-acd3-6838617d5fef" />

3. Live Application Deployment
<img width="952" height="511" alt="application running on ex IP" src="https://github.com/user-attachments/assets/7981725e-c839-4782-840c-2406bfffdd23" />
<img width="953" height="508" alt="EKS External Ip" src="https://github.com/user-attachments/assets/5960ced0-86df-4644-8255-a061c5f2f909" />


4.Kubernetes Cluster Health (Grafana Dashboard)
<img width="959" height="513" alt="graffana external ip" src="https://github.com/user-attachments/assets/f7c0b59e-e69d-4339-95b5-e8403c6bec84" />
<img width="950" height="512" alt="Graffana ss" src="https://github.com/user-attachments/assets/dd2c2824-00f1-49c4-b220-3963db960b69" />

5. AWS Infra Resources

<img width="959" height="511" alt="ec2 instances" src="https://github.com/user-attachments/assets/7d100bbd-fd47-4798-9a4d-3b0442a0dcc5" />
<img width="959" height="509" alt="eks" src="https://github.com/user-attachments/assets/da6c466a-ee8c-4da6-bbbc-b1c8b3465a75" />
<img width="953" height="508" alt="eks node grp" src="https://github.com/user-attachments/assets/a46281cb-c08b-4e1d-a686-d7d418a7b611" />

6.Docker Hub Repo
<img width="945" height="512" alt="docker hub ss" src="https://github.com/user-attachments/assets/a572c1ca-ddaa-445f-8213-0053760ef47f" />











