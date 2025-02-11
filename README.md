HEAD
# Terraform_Project
Create infrastructure on AWS using terraform

# AWS Terraform Infrastructure Setup

## 📌 Project Overview
This project automates the deployment of a scalable AWS infrastructure using Terraform. It provisions a Virtual Private Cloud (VPC) with public subnets, EC2 instances, an Application Load Balancer, and an S3 bucket.

## ⚡ Features
- **VPC & Subnets**: Creates a custom VPC with two public subnets.
- **Security Groups**: Allows HTTP and SSH access.
- **EC2 Instances**: Deploys two instances with user-data scripts.
- **Application Load Balancer**: Distributes traffic across instances.
- **S3 Bucket**: Provisions a bucket for additional storage.

## 📁 Project Structure

## 🚀 Getting Started
### Prerequisites
- Install Terraform: [Terraform Installation Guide](https://developer.hashicorp.com/terraform/downloads)
- Configure AWS CLI with your credentials.

### 🔹 Deployment Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Harsxch/Terraform_Project.git
   cd Terraform_Project/terraform

 c513718 (Added .gitignore to exclude Terraform cache and state files)
