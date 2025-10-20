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

AMI ID: ami-0e39053683c19ca0c

Description: ARM-Based NAT instance by Workmates Cybersecops Team

Region: Currently available only in ap-south-1 (Mumbai)

📊 Metrics Published

ConntrackCount

ConntrackUtilization

Memory and network utilization (optional via CloudWatch Agent)

🔧 Quick Start

Clone the repository and launch the instance using the provided ami-id.

📩 Support

For detailed documentation/nd-to-end implementation guidance or enterprise setup, contact:
📧 cybersecops@cloudworkmates.com

© 2025 Cloud Workmates | AWS & Cloud Security Labs

