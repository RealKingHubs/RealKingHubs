# Hi, I’m Odo Kingsley Uchenna 👋 
### Cloud & DevOps Engineer | Problem Solver

I am a Cloud Engineering student at **AltSchool Africa** (Class of 2025). I specialize in building secure, high-availability cloud infrastructure that moves away from manual "Click-Ops" toward full automation.

---

### Featured Project: Secure Web Application Deployment (AWS & Ansible)
[LINK_TO_REPO](https://github.com/RealKingHubs/aws-ansible-secure-web-deployment.git)

**The Challenge:** Deploy a high-availability web application with zero public exposure for backend servers.

**The Solution:**
*   **Architecture:** Designed a 3-tier system featuring **1 Bastion Host** (Public) and **2 Private Web Servers** (Private Subnet).
*   **High Availability:** Implemented an **AWS Application Load Balancer (ALB)** and **Target Groups** to distribute traffic, ensuring the application is only accessible via the ALB DNS.
*   **Security:** Enforced strict SSH access using **ProxyJump**. SSH is only permitted from my local machine to the Bastion, and from the Bastion to the Private Web Servers.
*   **Automation:** Used **Ansible** to automate the entire configuration installing NGINX, managing services, and deploying dynamic HTML content that displays unique Instance Hostnames/IPs.
*   **Git:** For version control. With git I have created a ready to deploy Ansible configuration files that has Bash Script attached to it check out the repo for more info on what the bash does.
  
**Key Outcome:** Successfully eliminated manual server configuration and ensured 100% network isolation for production workloads.

---

###  Additional Projects

#### Infrastructure Automation with Terraform.
[LINK_TO_REPO:](https://github.com/RealKingHubs/terraform-vpc-docker-automation.git)
*   **Problem:** Manual resource creation is slow and prone to "Human Error."
*   **Solution:** Used **Terraform** to provision a complete networking stack and deploy a containerized application on a public EC2 instance.
*   **Innovation:** Integrated `userdata.tpl` to bootstrap **Docker** automatically on launch, solving the "it works on my machine" problem.

---

###  Technical Toolkit

*   **Cloud Platform:** AWS (EC2, VPC, ALB, CLB, Target Groups, S3, IAM, Amplify)
*   **Automation & IaC:** Ansible (Configuration Management), Terraform (Provisioning)
*   **Security & Networking:** Bastion Hosts, SSH ProxyJump, Private/Public Subnets, Security Groups
*   **Containers & OS:** Docker, Linux Administration (Ubuntu/Amazon Linux), Bash Scripting
*   **Development:** Python, JavaScript, Git/GitHub

---

### Engineering Philosophy
> "Me: 1 | Terraform: 0. I believe that if an infrastructure isn't documented and automated, it isn't production-ready."

*   **Problem Solver:** I thrive on overcoming architectural challenges, such as configuring secure communication between isolated subnets.
*   **Documentation:** I document every workflow on **Medium** with professional architectural diagrams.

---

### Connect with Me
*   **<a href = "https://www.linkedin.com/in/kingsley-odo-8b81a6369/">LinkedIn</a>**
*   **<a href = "https://medium.com/@RealKingHubs">Medium</a>**
*   **<a href = "odokingsleyu@gmail.com">Email</a>** 

**Available for Remote Cloud Engineer/DevOps Internships**
