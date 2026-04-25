# 🚀 Solution: Automated EC2 Setup & App Deployment using Ansible

## 📌 Overview

We use **Ansible** to automate:

- Server configuration  
- Dependency installation  
- Application deployment  

---

## 📦 Prerequisites

- AWS EC2 Ubuntu instance  
- Ansible installed on control machine  
- SSH key pair (.pem file)  
- Inventory file with EC2 IP  

---

## 📁 Inventory File

```ini
[web]
<EC2_PUBLIC_IP> ansible_user=ubuntu ansible_ssh_private_key_file=path/to/key.pem