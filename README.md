<h1 align="center">Hi, I'm Odo Kingsley Uchenna </h1>
<h3 align="center">Cloud & DevOps Engineer | Software Developer</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/odokingsleyuchenna/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://medium.com/@RealKingHubs">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/>
  </a>
  <a href="mailto:odokingsleyu@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

### About Me

Cloud and DevOps Engineer with practical experience designing AWS environments, automating 
software deployments, and managing Linux infrastructure. Proficient in Infrastructure as Code using 
Terraform, container management with Kubernetes, and continuous integration via GitHub Actions. 
Strong technical background in high-availability networking, system monitoring, and live-incident 
troubleshooting. Focused on removing manual deployment problems, securing cloud perimeters, and 
helping engineering teams scale applications reliably.

---

### Technical Toolkit

<p>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>
</p>

---

### Featured Projects

#### 1. High Availability Drupal Setup: Automated Cloud Infrastructure

> To avoid application downtime caused by regional hardware failures, I built a multi-zone Drupal CMS platform on AWS. I used Terraform to provision a network across two availability zones, configuring public subnets for an Application Load Balancer and private subnets for two EC2 application servers and an Amazon RDS MySQL database. I wrote Ansible playbooks to dynamically configure the Linux servers, install PHP, set up Apache, handle database connection strings, and establish data synchronization across the runtime environments. I built a multi-stage GitHub Actions pipeline to compile the code, create Docker container versions, run automated smoke tests in a staging partition, and run a production update requiring a manual manager check. Finally, I deployed an ELK stack to gather log streams and linked Prometheus and Grafana dashboards to monitor web server response latency and trigger resource alerts.

   🔗 [View Repository](https://github.com/RealKingHubs/drupal-app-to-aws-production)

---

#### 2. AWS EKS Microservices Deployment: Project Bedrock Capstone

> For the AltSchool Cloud Engineering graduation examination, I built an automated infrastructure platform to run a microservices retail application. I used Terraform to establish a remote S3 backend and provision an Amazon EKS cluster named project-bedrock-cluster within a dedicated multi-AZ VPC in us-east-1. I migrated the application data layer from in-cluster containers to managed AWS resources, setting up secure private Amazon RDS instances and Amazon DynamoDB tables with credentials retrieved via AWS Secrets Manager. I installed the AWS Load Balancer Controller to expose the store interface through an Application Load Balancer and configured CloudWatch to collect both EKS control plane and container logs. Finally, I built a serverless pipeline where an S3 asset bucket triggers a Python Lambda function to process product images, and automated all changes using a GitHub Actions pipeline that plans on pull requests and applies on code merge.

🔗 [View Repository](https://github.com/RealKingHubs/retail-store-sample-app)

---

#### 3. Full Stack Automated Deployment: StartTech Architecture

> To implement a complete deployment pipeline for a growing full stack application, I separated corporate codebases into an application repository and an infrastructure repository. I wrote modular Terraform configurations to provision an Auto Scaling Group for a Golang backend API, an Application Load Balancer, an AWS ElastiCache Redis cluster, and an Amazon S3 static website bucket connected to a CloudFront CDN. I connected the backend to a MongoDB Atlas cluster and set up target CloudWatch log groups with IAM instance profiles for system auditing. I built independent GitHub Actions workflows that run security audits and tests, sync React assets directly to S3 with automated CloudFront cache invalidations, and package the Golang API as a Docker container for rolling updates on the auto scaling web nodes.

🔗 [Application Repository](https://github.com/RealKingHubs/starttech-application) | [Infrastructure Repository](https://github.com/RealKingHubs/starttech-infra)

---

---

#### 4. Production-Grade AWS Infrastructure with Terraform
> To prevent application downtime from single-point-of-failure issues, I built a self-healing, multi-zone web server infrastructure on AWS. I used Terraform to provision a multi-AZ VPC containing public and private subnets, redundant NAT Gateways, and an Application Load Balancer. I configured an Auto Scaling Group in the private subnets to scale Apache web servers based on traffic, and set up a Bastion Host for secure system updates. Storing the infrastructure state in an S3 bucket with DynamoDB locks stopped configuration conflicts and created a repeatable network setup.

🔗 [View Repository](https://github.com/RealKingHubs/terraform-vpc-docker-automation)

---

#### 5. Secure AWS Architecture with Ansible Automation
> Configuring web servers manually and exposing SSH credentials creates security vulnerabilities. I resolved this by designing an automated infrastructure setup that keeps all application servers hidden from the public internet. I created a multi-tier AWS network using a Bastion Host with an SSH ProxyJump configuration to protect the application tier. I wrote Ansible playbooks to handle OS configurations, install runtime packages, and deploy the web applications over these private channels. This process closed port 22 to the public internet and standardized configuration management across all web servers.

🔗 [View Repository](https://github.com/RealKingHubs/aws-ansible-secure-web-deployment)

---
#### 6. CI/CD Pipeline — Containerized Node.js to AWS ECS Fargate
> Using static AWS keys in automation code creates security risks if the repository is compromised. I built a continuous integration and deployment pipeline to securely ship a Node.js application to cloud hosting. I set up GitHub Actions workflows to authenticate via OpenID Connect, allowing the pipeline to fetch short-lived AWS session tokens instead of using hardcoded secrets. The pipeline builds a multi-stage Docker image, runs tests, pushes the build to Amazon ECR, and triggers a rolling update on AWS ECS Fargate. The project keeps credentials safe and guarantees the application stays online during code updates.

🔗 [View Repository](https://github.com/RealKingHubs/CICD-Automation-Pipeline)

---

### Certifications & Awards

<table align="center" border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/2f6d0c27-4548-4917-863c-3c4781dcc119" width="280" alt="cloud engineering" style="display:block; margin:5px;"/>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/8b664ba4-a52c-4e0b-816f-ad0e7b078385" width="280" alt="Kingsley Uchenna Odo" style="display:block; margin:5px;"/>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/d1a4cc45-72df-48a3-ad7b-c0d8c2670c21" width="280" alt="Kingsley Uchenna Odo BLA" style="display:block; margin:5px;"/>
    </td>
  </tr>
</table>

---

### My Engineering Philosophy

> *"If an infrastructure isn't documented and automated, it isn't production-ready."*

---
