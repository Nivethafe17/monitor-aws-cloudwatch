# 🌩️ Cloud Monitoring using AWS CloudWatch

**Name:** Nivetha P  
**Intern ID:** CT04DN74  
**Company:** CodTech IT Solutions  
**Domain:** Cloud Computing  
**Internship Duration:** 4 Weeks  
**Mentor:** Neela Santhosh  

---

## 📝 Task Objective

The objective of this task is to **set up monitoring for a cloud-based application using AWS CloudWatch**, and to provide configured alerts and a custom dashboard that showcases system metrics in real-time. This includes launching a virtual machine (EC2), collecting system-level metrics, creating alarms, and building a visual dashboard.

---

## ✅ Task Deliverables

- ✅ Launch EC2 instance with monitoring enabled  
- ✅ Install and configure the CloudWatch Agent  
- ✅ Collect custom metrics (CPU, Memory, Disk)  
- ✅ Create an alarm for CPU Utilization threshold  
- ✅ Trigger the alarm with high CPU usage  
- ✅ Build and display a CloudWatch dashboard  
- ✅ Upload all screenshots and documentation to GitHub

---

## ⚙️ Step-by-Step Implementation

### 1. **Launch EC2 Instance**
- Used Amazon Linux 2 AMI on a `t2.micro` instance (Free Tier).
- Enabled basic and detailed monitoring.
- Created a new key pair for secure access.
- Allowed SSH (port 22) through security groups.

### 2. **Install & Configure CloudWatch Agent**
- Connected via SSH and installed the agent using the following command:
  ```bash
  sudo yum install amazon-cloudwatch-agent -y
