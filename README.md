# GCP VM Auto-Scaling Project

## Project Overview
This project demonstrates the creation of a scalable and secure Virtual Machine infrastructure on Google Cloud Platform using:

- Compute Engine VM
- Instance Template
- Managed Instance Group (MIG)
- CPU-based Auto-scaling
- IAM configuration
- Firewall rules

---

## Architecture Components

1. Instance Template  
   Defines machine type, OS image, disk, and configuration.

2. Managed Instance Group  
   Automatically manages identical VM instances.

3. CPU-based Auto-scaling  
   Automatically increases or decreases VM instances based on CPU utilization.

4. Firewall Rules  
   Configured to allow HTTP (80) and HTTPS (443) traffic.

5. IAM Roles  
   Configured to ensure secure access control.

---

## Auto-scaling Configuration

- Target CPU utilization: 60%
- Minimum instances: 1
- Maximum instances: 3
- Scaling policy: Based on average CPU usage

When CPU usage increases beyond threshold, new instances are automatically created.
When CPU usage decreases, instances are reduced automatically.

---

## Security Implementation

- Firewall rules to control inbound traffic
- IAM roles for access control
- Default VPC network configuration

---

## Repository Purpose

This repository contains documentation for the GCP VM auto-scaling setup project.
