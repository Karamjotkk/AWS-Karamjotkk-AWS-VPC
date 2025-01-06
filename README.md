# AWS VPC Using Terraform

Welcome to the **AWS VPC Using Terraform** repository! 🚀

In this project, we have created a fully functional **AWS Virtual Private Cloud (VPC)** using **Terraform**. This setup demonstrates how to build a scalable and secure infrastructure on AWS with multiple components integrated seamlessly.

## Project Overview

The infrastructure created includes:

- **AWS VPC**: A Virtual Private Cloud to isolate your resources and control networking.
- **2 EC2 Instances**: Deployed in **public subnets** across **two different availability zones** to ensure high availability.
- **S3 Bucket**: Connected to the EC2 instances for object storage.
- **Elastic Load Balancer (ELB)**: Ensures load distribution across the EC2 instances for better fault tolerance.
- **Security Groups**: Configured to control inbound and outbound traffic to secure the EC2 instances and other components.

## Key Components

1. **VPC**: Provides a secure and isolated environment for hosting resources.
2. **EC2 Instances**: Compute resources deployed across two public subnets in different availability zones.
3. **S3 Bucket**: For object storage, connected with the EC2 instances.
4. **Load Balancer**: Distributes incoming traffic between EC2 instances for better performance and reliability.
5. **Security Groups**: Defines firewall rules for enhanced security.


## Requirements

- **Terraform** (latest version)
- **AWS CLI** configured with appropriate credentials
- Basic knowledge of AWS services and Terraform

## How to Use

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/AWS-VPC.git


## Requirements

- **Terraform** (latest version)
- **AWS CLI** configured with appropriate credentials
- Basic knowledge of AWS services and Terraform

## How to Use

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/AWS-VPC.git

2. **Navigate to the project directory**:
   ```bash
   cd AWS-VPC
   
3. **Initialize Terraform**:
   ```bash
   terraform init

4. **Apply the Terraform configuration**:
   ```bash
   terraform apply
