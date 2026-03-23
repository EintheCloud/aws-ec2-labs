# aws-ec2-labs
Hands on EC2 labs - launch, SSH, configure and terminate instances on AWS
# AWS EC2 Labs ☁️

## Overview
Hands on EC2 labs practicing instance launch, 
SSH connection, and termination on AWS free tier.

## Labs Completed
- Lab 01 — Launch and SSH into EC2 instance
- Lab 02 — Stop, start, terminate lifecycle  
- Lab 03 — Solo launch without guidance
- Lab 04 — Terminal SSH from Mac

## Key Concepts Learned
- AMI selection and free tier eligibility
- Key pair creation and chmod permissions
- SSH from Mac terminal
- Public vs private IP addresses
- Instance lifecycle — running, stopped, terminated

## Commands Reference
```bash
mkdir ~/.aws-keys
mv ~/Downloads/key.pem ~/.aws-keys/
chmod 400 ~/.aws-keys/key.pem
ssh -i ~/.aws-keys/key.pem ec2-user@[IP]
