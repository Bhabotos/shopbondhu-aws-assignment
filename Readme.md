# ShopBondhu AWS Assignment

## Project Overview
This project demonstrates AWS networking and web server deployment using a VPC with public and private subnets.

## AWS Services Used
- Amazon VPC
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Amazon EC2
- Security Groups
- Nginx Web Server
- Docker

## Network Configuration
- VPC: shopbondhu-vpc
- VPC CIDR: 10.0.0.0/16
- Public Subnet: 10.0.1.0/24
- Private Subnet: 10.0.2.0/24

## EC2 Instances
- Public EC2: shopbondhu-web
- Private EC2: shopbondhu-private-ec2
- Private EC2 IP: 10.0.2.25

## Implementation
1. Created a VPC and public/private subnets.
2. Configured an Internet Gateway and NAT Gateway.
3. Configured public and private route tables.
4. Launched public and private EC2 instances.
5. Installed and configured Nginx on the private EC2 instance.
6. Verified HTTP connectivity from the public EC2 to the private EC2.

## Screenshots
See the `screenshots` folder for AWS configuration and testing evidence.

## Status
AWS infrastructure deployment and connectivity testing completed.
