# -AWS-Solutions-Architect---Associate-
AWS Solutions Architect - Associate  Proposed by Manara program


# Scalable Web Application on AWS (EC2 + ALB + Auto Scaling)

This project deploys a highly available and scalable web application on AWS using EC2 instances behind an Application Load Balancer (ALB) with Auto Scaling Groups (ASG).  
The goal is to demonstrate scalable compute infrastructure without using a database (stateless deployment).

---

## 📍 Architecture Overview (No Database)

The application is deployed across multiple Availability Zones to ensure fault tolerance.  
ALB distributes traffic to EC2 instances managed by an Auto Scaling Group.


---

## 🛠 AWS Services Used

| Service | Purpose |
|---------|---------|
| **EC2** | Hosts the web application |
| **Application Load Balancer** | Distributes traffic across instances |
| **Auto Scaling Group** | Scales instances based on demand |
| **IAM Role + Instance Profile** | Secure permissions for EC2 |
| **CloudWatch + SNS** | Monitoring + alerts |
| **S3 (optional)** | Store static assets or logs |
| **SSM Session Manager** | Secure access without SSH |

>No database is used in this version — the application runs stateless.

---

## 📂 Repository Structure


