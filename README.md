Terraform AWS VPC Infrastructure 🚀










Infrastructure as Code project that provisions a production-style AWS networking environment using Terraform on Amazon Web Services.

This project creates a secure VPC architecture with public and private networking components following real DevOps infrastructure design.

Architecture 🌐
                Internet
                   │
           Internet Gateway
                   │
                 VPC
             10.0.0.0/16
                   │
        ┌──────────┴──────────┐
        │                     │
   Public Subnet         Private Subnet
   10.0.1.0/24           10.0.2.0/24
        │                     │
    NAT Gateway        Private Resources
        │
   Public Route Table
Tech Stack ⚙️
Tool	Purpose
Terraform	Infrastructure as Code
Amazon Web Services	Cloud Provider
Git	Version Control
GitHub	Code Repository
Project Structure 📁
terraform-vpc-project/
│
├── provider.tf
├── main.tf
├── variables.tf
├── terraform.tfvars
├── outputs.tf
├── .gitignore
└── README.md
Terraform Workflow ⚡

Initialize Terraform

terraform init

Check configuration

terraform validate

Format code

terraform fmt

Preview infrastructure

terraform plan

Create infrastructure

terraform apply

Destroy infrastructure

terraform destroy
Infrastructure Created 🏗️

✔ VPC
✔ Public Subnet
✔ Private Subnet
✔ Internet Gateway
✔ NAT Gateway
✔ Elastic IP
✔ Public Route Table
✔ Private Route Table
✔ Route Table Associations

DevOps Concepts Demonstrated

Infrastructure as Code

Cloud Networking

Automated Infrastructure Provisioning

Git-based Infrastructure Management

Production VPC Architecture

Author 👨‍💻

Chandan Gadewar
Aspiring DevOps Engineer
