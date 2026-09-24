# 👋 Hi, I'm Mohamed Sarbudeen

<p align="center">
  <img src="./sarbu04-profile-roles.gif" alt="Cloud and DevOps roles" width="700">
</p>

<p align="center">
  <strong>☁️ Cloud & DevOps Engineer | AWS | Azure | Kubernetes | Linux</strong>
</p>

<p align="center">
  🏆 <strong>AWS Certified Solutions Architect – Associate (SAA-C03)</strong>
</p>

---

## 👨‍💻 About Me

I'm a **Cloud & DevOps Engineer** with around **2 years of experience** in cloud operations, production support, infrastructure monitoring, Kubernetes, and CI/CD.

My experience includes supporting production workloads on **AWS and Azure**, managing Linux environments, monitoring Kubernetes clusters, troubleshooting production incidents, and supporting application deployments through CI/CD pipelines.

I'm currently strengthening my hands-on skills in:

**Cloud Engineering • DevOps • Kubernetes • Infrastructure as Code • CI/CD • Automation • Observability**

> **Learn → Build → Troubleshoot → Automate → Document**

---

# 🛠️ Technical Skills

## ☁️ Cloud Platforms

<p align="left">
  <img src="https://skillicons.dev/icons?i=aws,azure" height="50" alt="AWS Azure">
</p>

### AWS
**EC2** • **S3** • **IAM** • **VPC** • **Route 53** • **RDS**  
**Elastic Load Balancing** • **Auto Scaling** • **Lambda** • **CloudWatch**  
**ECR** • **ECS** • **EKS**

### Azure
**Virtual Machines** • **Virtual Network** • **AKS**  
**Key Vault** • **Managed Identities** • **Storage Accounts** • **Resource Groups**

---

## 🐳 Containers & Orchestration

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,helm" height="50" alt="Docker Kubernetes Helm">
</p>

**Docker** • **Kubernetes** • **Helm**  
**Amazon EKS** • **Azure AKS**

---

## ⚙️ DevOps & CI/CD

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,jenkins,ansible" height="50" alt="Git GitHub Jenkins Ansible">
</p>

**Git** • **GitHub** • **GitHub Actions**  
**Jenkins** • **Azure DevOps** • **CI/CD** • **Ansible**

---

## 🐧 Linux & Automation

<p align="left">
  <img src="https://skillicons.dev/icons?i=linux,bash,python,yaml" height="50" alt="Linux Bash Python YAML">
</p>

### Operating Systems

**Ubuntu** • **CentOS** • **Red Hat** • **Amazon Linux** • **Windows Server**

### Automation & Administration

**Bash / Shell Scripting** • **Python** • **YAML**  
**SSH** • **DNS** • **System Administration**

---

## 📊 Monitoring & Observability

<p align="left">
  <img src="https://skillicons.dev/icons?i=prometheus,grafana" height="50" alt="Prometheus Grafana">
</p>

**New Relic** • **New Relic APM** • **NRQL**  
**Datadog** • **ELK** • **CloudWatch**

### Monitoring & Operations

**Infrastructure Monitoring**  
**Application Performance Monitoring**  
**Alerting & Alert Tuning**  
**Incident Management**  
**Root Cause Analysis (RCA)**

---

## 🗄️ Databases & Application Servers

<p align="left">
  <img src="https://skillicons.dev/icons?i=mysql,apache" height="50" alt="MySQL Apache">
</p>

**MySQL** • **AWS RDS**  
**Apache** • **Tomcat** • **PHPMyAdmin**

---

## 🌐 Networking & Security

**TCP/IP** • **DNS** • **SSH** • **IAM**  
**VPC** • **Subnets** • **Route Tables**  
**Security Groups** • **Load Balancing**

**iptables** • **firewalld** • **Key-based Authentication**

---

# 💼 Professional Experience

## ☁️ Associate Consultant – Cloud Operations

**AWAN Infotech Pvt. Ltd. | Chennai, Tamil Nadu**

`Mar 2025 – Apr 2026`

- Supported production applications hosted on **AWS EC2 and Azure Virtual Machines**.
- Managed and monitored **multi-tenant Kubernetes clusters** across production environments.
- Used **New Relic Infrastructure and APM** for application and infrastructure monitoring.
- Created **NRQL dashboards and alerts** and performed alert tuning.
- Supported production deployments using **Azure DevOps CI/CD pipelines**.
- Monitored CPU, memory, disk, network, and application performance across **1,000+ Windows and Linux servers**.
- Supported **VM-to-Kubernetes migration** activities with senior engineers.
- Managed production incidents using **Ivanti Service Manager**.
- Performed **Root Cause Analysis (RCA)** for production issues.

---

## 🐧 Linux & Cloud Administrator

**Keystones Cloud Tech Pvt. Ltd. (HOSTZOP) | Chennai, Tamil Nadu**

`Apr 2022 – Dec 2022`

- Administered **Linux servers** including Ubuntu, CentOS, and Red Hat.
- Provisioned and migrated virtual machines and hosting environments.
- Troubleshot **SSH connectivity, DNS resolution, web server, and database issues**.
- Installed and configured **Apache, Tomcat, MySQL, and PHPMyAdmin**.
- Performed OS patching using **YUM/RPM**.
- Managed **LVM, disk partitions, volume resizing, and storage**.
- Performed backup and restoration of customer data.
- Managed Linux server issues and customer tickets within SLA.

---

# 🚀 Featured Project

## ☁️ Deploy Java Application on AWS – 3-Tier Architecture

A hands-on AWS project demonstrating deployment of a Java web application using a production-style **3-tier architecture**.

### Architecture

```text
                         INTERNET
                            │
                            ▼
                   ┌─────────────────┐
                   │       ALB       │
                   │  Public Subnet  │
                   └────────┬────────┘
                            │
                            ▼
              ┌──────────────────────────┐
              │     Private App Tier     │
              │                          │
              │   EC2-A       EC2-B      │
              │     │           │        │
              │   Nginx       Nginx      │
              │     │           │        │
              │  Tomcat      Tomcat      │
              │     │           │        │
              │  Java App    Java App    │
              └────────────┬─────────────┘
                           │
                           │ TCP 3306
                           ▼
                  ┌─────────────────┐
                  │    RDS MySQL    │
                  │  Private DB Tier│
                  └─────────────────┘
AWS Services
Amazon VPC
EC2
Application Load Balancer
Target Groups
Auto Scaling
Amazon RDS MySQL
Internet Gateway
Security Groups
Route Tables
IAM
AWS Systems Manager
Application Stack
Java
Spring Boot
Maven
Tomcat
Nginx
MySQL
Key Implementation
Designed a custom VPC with public, application, and database subnets.
Deployed application servers in private subnets.
Configured ALB as the public entry point.
Configured Target Group health checks.
Deployed Java application using Tomcat.
Configured Nginx → Tomcat reverse proxy flow.
Connected the Java application to Amazon RDS MySQL.
Configured separate Security Groups for:
ALB
Application EC2
RDS
Configured Auto Scaling Group across two Availability Zones.
Tested EC2 failure and automatic instance replacement.
Verified ALB traffic routing to healthy targets.
Troubleshot application, networking, Tomcat, Nginx, and database connectivity issues.
🔗 Project Repository

Deploy-Java-Application-on-AWS-3-Tier-Architecture

🎓 Education
<table> <tr> <td align="center" width="50%"> <h3>🎓 MCA</h3> <strong>Master of Computer Applications</strong> <br> University of Madras <br> 📅 2022 – 2024 <br> 💻 Computer Applications </td>
<td align="center" width="50%">
  <h3>🎓 B.Sc. Computer Science</h3>
  <strong>Bachelor of Science</strong>
  <br>
  University of Madras
  <br>
  📅 2017 – 2020
  <br>
  🧑‍💻 Started my journey into IT
</td>
</tr> </table>
🧑‍💻 Education → Career
<p align="center">

🎓 Computer Science
 → 
🐧 Linux
 → 
☁️ Cloud
 → 
⚙️ DevOps
 → 
☸️ Kubernetes
 → 
🚀 Cloud Engineering

</p>
🏆 Certification
<p align="center"> <img src="https://img.shields.io/badge/AWS-Certified%20Solutions%20Architect--Associate-orange?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Certified Solutions Architect Associate" > </p> <p align="center"> <strong>AWS Certified Solutions Architect – Associate (SAA-C03)</strong> </p>
📚 Currently Learning & Building
☁️ Cloud

AWS Cloud Architecture
VPC & Networking
High Availability
Load Balancing
Infrastructure Design

⚙️ DevOps

Terraform
Infrastructure as Code
CI/CD Pipelines
Docker
GitHub Actions

☸️ Kubernetes

Kubernetes Administration
Amazon EKS
Deployments
Services
Ingress
Helm

📊 Observability

New Relic
Datadog
ELK
CloudWatch
Infrastructure Monitoring

🎯 Career Focus

I'm focused on building practical skills in:

Cloud Engineering • DevOps • Kubernetes • Linux
Infrastructure as Code • CI/CD • Monitoring & Observability

Learn → Build → Troubleshoot → Automate → Document

🤝 Let's Connect
<p align="left"> <a href="https://www.linkedin.com/in/sarbu-deen/"> <img src="https://img.shields.io/badge/LinkedIn-Mohamed%20Sarbudeen-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" > </a> <a href="mailto:msarbudeen1@gmail.com"> <img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" > </a> </p>
<p align="center">

☁️ Cloud  • 
⚙️ DevOps  • 
☸️ Kubernetes  • 
🐧 Linux  • 
📊 Observability

</p> <p align="center">

⭐ Thanks for visiting my profile!

</p> ```
