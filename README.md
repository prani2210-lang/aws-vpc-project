# AWS 2-Tier Architecture Project

## Overview
This project demonstrates a secure two-tier architecture using AWS services.

## Services Used
- Amazon EC2 (Web + App servers)
- Amazon VPC (Public and Private Subnets)
- Internet Gateway & NAT Gateway
- Security Groups & IAM Roles
- Amazon CloudWatch for monitoring

## Steps Performed
1. Created custom VPC with 2 public and 2 private subnets.
2. Configured Internet Gateway and route tables.
3. Launched EC2 instances in public subnet for web tier.
4. Set up private EC2 instance (App Tier) accessible via Bastion Host.
5. Configured Security Groups to restrict SSH and HTTP access.
6. Verified access and monitoring through CloudWatch.

## Outcome
The setup allows secure communication between public and private subnets with restricted inbound access.

## Tools Used
AWS Management Console, IAM, EC2, VPC, CloudWatch

---

⭐ **Author:** Pranitha M Pai
