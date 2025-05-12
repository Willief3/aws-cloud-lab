# AWS Cloud Lab – EC2 + ALB + ACM

This project is a hands-on introduction to core AWS services, designed to help build foundational cloud security and infrastructure skills.

---

## Overview

In this lab, I:

- Launch a PHP-based web app on EC2
- Secure it behind an Application Load Balancer (ALB) with HTTPS (ACM certificate)
- Implement IAM roles with least privilege access
- Set up security logging and monitoring with GuardDuty, CloudTrail, and VPC Flow Logs

---

## Key AWS Services Used

- **EC2** (Amazon Linux 2023)
- **IAM** (roles, trust policies, permission boundaries)
- **ALB + ACM** (SSL termination via HTTPS)
- **S3** (for secure log storage)
- **GuardDuty** (threat detection and alerting)

---

## Screenshots

Visuals and architecture diagrams are available under:
- [diagrams/](https://github.com/Willief3/aws-cloud-lab/tree/main/diagrams)
- (To be updated with ALB/EC2/SG screenshots as lab progresses)

---
## Project Insights & Challenges

During this project, I encountered real-world issues with HTTPS routing and AWS permissions:

- Learned that HTTPS termination should happen at the ALB, not EC2.
- Improved security by configuring EC2 to only accept traffic from the ALB.
- Troubleshot SSL mismatch warnings due to domain/cert alignment.
- Gained confidence in IAM policy usage and Security Group scoping.
---

## Config Files

Explore setup scripts and policies under:
- [configs/](https://github.com/Willief3/aws-cloud-lab/tree/main/configs)

Includes:
- EC2 user data for bootstrapping Apache + PHP
- IAM policy examples
- Security group rule plans (planned)

---

## Status

This is an evolving learning project. Additional components planned:
- VPC architecture diagram
- GuardDuty alert simulation + response
- Optional CloudFormation automation

---
