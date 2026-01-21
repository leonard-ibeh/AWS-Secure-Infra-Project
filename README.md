# AWS Secure Infra Project

## 🛡️ Security Overview
This project demonstrates how to deploy a hardened AWS infrastructure using the Principle of Least Privilege.

## 🚀 Implemented Security Controls
* **Identity & Access:** IAM roles with granular permissions (No Root usage).
* **Data Protection:** S3 buckets with "Block Public Access" and AES-256 encryption.
* **Network Security:** VPC designed with Private Subnets and Security Groups restricted to specific IPs.

## 🛠️ Tools Used
* **Terraform:** For Infrastructure as Code (IaC).
* **AWS CLI:** For manual configuration and audits.
* **Checkov/tfsec:** For static analysis security scanning.
