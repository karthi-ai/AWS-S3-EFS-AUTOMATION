# AWS S3 and EFS Automation

## Project Overview
This project demonstrates shared storage using Amazon EFS across EC2 instances and automated synchronization of files to Amazon S3.

## AWS Services
- Amazon EC2
- Amazon EFS
- Amazon S3
- AWS IAM
- Linux cron

## What I Practiced
- Configuring shared storage across EC2 instances
- Using an EC2 IAM role for AWS CLI access
- Synchronizing files to S3 with AWS CLI
- Scheduling recurring tasks with cron
- Troubleshooting Linux permissions and automation logs

## Architecture
EC2 Instance 1 ─┐
                ├── Amazon EFS ── AWS CLI / cron ── Amazon S3
EC2 Instance 2 ─┘

## Security Notes
- Use an IAM role with least-privilege permissions.
- Never commit AWS access keys, private keys, or credentials.
- Review AWS resources and costs after testing.
