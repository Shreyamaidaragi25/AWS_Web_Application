# AWS_Web_Application
Scalable web application using AWS VPC, Load Balancer, Auto Scaling and private EC2 instances
# AWS Scalable Web Application

## 📌 Project Overview
This project demonstrates a highly available and scalable web application deployed on AWS using core cloud services.

## 🏗 Architecture
- Custom VPC with 2 public and 2 private subnets
- Application Load Balancer (public)
- Auto Scaling Group
- EC2 instances in private subnet
- Security Groups for controlled access

## 🔄 Architecture Flow
User → Load Balancer → Auto Scaling EC2 → Response

## ⚙️ Services Used
- Amazon EC2
- Application Load Balancer
- Auto Scaling Group
- Amazon VPC
- Security Groups

## 🔐 Security Implementation
- EC2 instances deployed in private subnet
- No direct public access to EC2
- Only Load Balancer can communicate with EC2

## 📈 Auto Scaling
- Configured using target tracking policy
- Scales based on CPU utilization

## 🌐 Output
The application displays:
"Hello from Auto Scaling Server"

## 📸 Screenshots
<img width="689" height="227" alt="Screenshot 2026-04-02 184815" src="https://github.com/user-attachments/assets/6fed76b6-6abc-4a15-9052-6bf474cee60e" />


## 🚀 Key Learnings
- VPC architecture design
- Load balancing concepts
- Auto Scaling implementation
- Secure cloud architecture

## 👩‍💻 Author
Shreya Maidaragi
