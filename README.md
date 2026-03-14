# AWS EC2 & EBS Storage Management Lab

This project demonstrates the deployment of a dual-OS web environment (Linux & Windows) on AWS, focusing on persistent storage management using Amazon EBS.

## 🚀 Tech Stack
* **Cloud Provider:** AWS (Amazon Web Services)
* **Compute:** EC2 (Amazon Elastic Compute Cloud) - t3.micro
* **Storage:** EBS (Elastic Block Store) - gp3
* **Web Servers:** Apache (Linux) & IIS (Windows)

## 📋 Task Overview
1. **Launch EC2 Instances:** Deployed one Amazon Linux 2023 and one Windows Server 2025 instance.
2. **Web Server Setup:** Configured automated Apache installation on Linux via User Data and manual IIS setup on Windows.
3. **EBS Management:** Created a 5 GB EBS volume and successfully attached it to the Windows instance.
4. **Data Persistence:** Initialized and formatted the volume within the Windows OS.
5. **Backup & Recovery:** Created a point-in-time snapshot of the volume and restored it into a new EBS volume.
