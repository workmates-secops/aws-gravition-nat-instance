# 🚀 AWS NAT Instance with Monitoring & Hardening

[![AWS](https://img.shields.io/badge/AWS-NAT%20Instance-orange?logo=amazonaws)](https://aws.amazon.com/vpc/)
[![CloudWatch](https://img.shields.io/badge/Monitoring-CloudWatch-blue?logo=amazoncloudwatch)](https://aws.amazon.com/cloudwatch/)
[![Security](https://img.shields.io/badge/Security-Hardened-green?logo=shield)](#)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)

A lightweight, customizable **AWS NAT Instance** setup that provides:
- ✅ NAT routing with `iptables`
- 📊 CloudWatch metrics for connection tracking
- 💥 Load simulation from private instances
- 🔒 SSH & EC2 Instance Connect hardening

---
🛡️ NAT Instance with CloudWatch Conntrack Monitoring

This project demonstrates how to deploy and monitor a custom NAT Instance in AWS with enhanced visibility using CloudWatch metrics for connection tracking and memory utilization.

🚀 Features

Lightweight ARM-based NAT instance optimized for private subnet egress.

Custom CloudWatch metrics for nf_conntrack_count and utilization.

Supports continuous traffic testing for load simulation.

Easily customizable iptables and monitoring scripts.

🖥️ AMI Details

AMI ID: ami-0addc2ad0ca5dc615

Description: ARM-Based NAT instance by Workmates Cybersecops Team

Region: Currently available only in ap-south-1 (Mumbai)

💰 Cost Benefits of ARM (Graviton)

Up to 40% lower cost compared to Intel/AMD-based instances.

Better price-to-performance ratio for network-bound workloads like NAT.

Lower power consumption and optimized for continuous lightweight traffic handling.

📊 Metrics Published

ConntrackCount

ConntrackUtilization

Memory and network utilization (optional via CloudWatch Agent)

<img width="1350" height="609" alt="image" src="https://github.com/user-attachments/assets/d4797bb6-c4c0-4f70-8b19-17ae8dab952b" />



🔧 **Quick Start**

Clone the repository and launch the instance using the provided ami-id.

<img width="1571" height="738" alt="image" src="https://github.com/user-attachments/assets/bf33f1a6-a639-4a93-a26b-6c26d9b79aa7" />



📩 Support

For detailed documentation/end-to-end implementation guidance or enterprise setup, contact:
📧 cybersecops@cloudworkmates.com

© 2025 Cloud Workmates | AWS & Cloud Security/Cybersecurity Practice 

