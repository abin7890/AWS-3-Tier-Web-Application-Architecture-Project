# AWS-3-Tier-Web-Application-Architecture-Project
## 🚀 Project Overview
This project demonstrates the design and implementation of a highly available, secure, and scalable 3-tier web application architecture on AWS.

## 🏗️ Architecture
The application is divided into three layers:
- Web Tier (EC2 + Load Balancer)
- Application Tier (EC2 in private subnet)
- Database Tier (Amazon Aurora RDS)

## 🔧 Services Used
- Amazon VPC
- EC2 Instances
- Elastic Load Balancer (ELB)
- Amazon Aurora (RDS)
- Auto Scaling (optional)

## 🔐 Key Features
- Multi-AZ deployment for high availability
- Public and Private subnets for security
- Load balancing for traffic distribution
- Database replication using Read Replica
- Network isolation using Security Groups and NACLs

## 📸 Architecture Diagram
![Architecture](architecture-diagram.png)

## 📌 Steps Implemented
1. Created VPC with CIDR block
2. Configured public and private subnets
3. Deployed EC2 instances for web & app tiers
4. Configured ELB for traffic routing
5. Set up Amazon Aurora with Read Replica
6. Applied security groups and routing tables

## 📈 Outcome
- Improved scalability and fault tolerance
- Ensured secure communication between tiers
- Learned real-world cloud architecture design

## 👨‍💻 Author
Abin
