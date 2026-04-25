# 🚧 Problem Statement: Automated Deployment of Fullstack App on EC2

## 📌 Context

In modern cloud environments, manually setting up servers and deploying applications is time-consuming, error-prone, and not scalable. Teams need a repeatable and automated way to provision infrastructure and deploy applications.

---

## ❗ Problem

We need to:

- Provision an Ubuntu server on AWS EC2  
- Configure the server with required dependencies  
- Deploy a fullstack application  
- Ensure the application is accessible over HTTP  

Currently, this process is done manually, which leads to:

- ❌ Inconsistent environments  
- ❌ Configuration errors  
- ❌ Slow deployment cycles  
- ❌ Lack of scalability  

---

## 🎯 Objective

Design an automated solution using **Ansible** that:

1. Sets up an Ubuntu EC2 instance  
2. Installs required software (Python3, Node.js)  
3. Clones the application repository  
4. Runs the application on port **3000**  
5. Makes it accessible via HTTP  

---

## 📦 Application Details

- Repository: https://github.com/Tsaihemanth150/fullstackapp  
- Runtime: Node.js  
- Port: 3000  

---

## ✅ Expected Outcome

A fully automated, repeatable deployment process that:

- Eliminates manual setup  
- Ensures consistency across environments  
- Reduces deployment time  
- Enables easy scaling in future  