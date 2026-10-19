# AWS S3 and EFS Automation

## Project Overview
This project demonstrates shared storage across two Amazon EC2 instances using Amazon EFS and automated synchronization of files to Amazon S3.

## AWS Services
- Amazon EC2
- Amazon EFS
- Amazon S3
- AWS IAM
- Linux cron

## Skills Practiced
- Configuring shared storage across EC2 instances
- Using IAM roles for AWS CLI access
- Synchronizing files to Amazon S3 with AWS CLI
- Scheduling recurring tasks with cron
- Troubleshooting Linux and AWS CLI errors

## Architecture
EC2 Instance 1 ─┐
                ├── Amazon EFS ── AWS CLI / cron ── Amazon S3
EC2 Instance 2 ─┘

## Security
- Use least-privilege IAM permissions.
- Never commit AWS credentials or private keys.
- Monitor AWS costs and remove unused resources.
