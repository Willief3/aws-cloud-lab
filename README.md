# aws-cloud-lab
This project is intended as an intro into AWS framework and provides assistance in building hands on skills. 

# AWS Web App Lab – EC2 + ALB + ACM

🚧 **Project in progress** – this repo documents my learning as I build and secure a web application using AWS services.

## ☁️ Overview

A simple cloud lab where I:
- Launch a PHP-based web app on EC2
- Secure it behind an Application Load Balancer (ALB) with HTTPS (ACM cert)
- Use IAM roles for least privilege
- Set up logging and monitoring (GuardDuty, CloudTrail, VPC Flow Logs)

## Key Services Used

- EC2 (Amazon Linux 2023)
- IAM (roles, policies)
- ALB + ACM (HTTPS termination)
- S3 (hosted logs, secure buckets)
- GuardDuty (threat detection)

## 📸 Screenshots

- Avaliable under: 

##  Lessons Learned

- How IAM trust policies and role assumptions work
- Why HTTPS termination at the ALB is more secure and scalable
- How to limit EC2 Security Group exposure using ALB SGs
- What GuardDuty alerts look like for common attack patterns

## 🔧 Config Files

- Avalilable under:


