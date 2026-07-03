# Project 2: The Server Commander (AWS EC2)

## Overview
Deployed a custom webpage on a live AWS EC2 instance running Amazon Linux 2023, 
using Nginx as the web server — completed as part of the DecodeLabs Cloud 
Computing Internship.

## What I Did
1. Launched an EC2 instance (t2.micro, Amazon Linux 2023, Free Tier)
2. Created and secured a key pair (.pem) for SSH authentication
3. Configured Security Group rules:
   - SSH (port 22) restricted to My IP
   - HTTP (port 80) open to public
   - HTTPS (port 443) open to public
4. Connected to the instance via SSH from Windows PowerShell
5. Installed and started Nginx web server
6. Created a custom `index.html` welcome page
7. Verified the page was live via public IP in browser

## Tools Used
- AWS EC2
- Amazon Linux 2023
- Nginx
- Windows PowerShell (OpenSSH)

## Screenshots
See the images in this repository for proof of each step:
- EC2 instance running
- Security group configuration
- SSH connection established
- Nginx active status
- Live website in browser

## Key Learnings
- Difference between Security Groups (firewall) and SSH key-based authentication
- Shared Responsibility Model in cloud computing
- Basic Linux server administration (dnf, systemctl, nano)
