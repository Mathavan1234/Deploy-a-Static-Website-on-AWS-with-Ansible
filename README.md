# 🚀 Deploying a Static Website on AWS with Ansible  

This project demonstrates how to deploy a **static website** on **AWS** using **Ansible**, automating the setup of EC2 instances, configuring security groups, and installing necessary dependencies.  

---

## 📂 Project Files  

- **ansible.cfg** – Configuration file to test the connection between the Ansible Web Server and EC2 Web Servers.  
- **inventory** – Contains the **Private IP Addresses** of both EC2 Web Servers (AZ1 & AZ2), ensuring **High Availability** across two AWS Availability Zones.  
- **deploy-jupiter-website.yaml** – Ansible playbook that automates the installation of static web content and required services on the Ansible Web Server.  

---

## 🛠️ Deployment Process  

1. **Set up AWS infrastructure** – VPC, Subnets, Route Tables, Security Groups, and EC2 Instances.  
2. **Configure Ansible Server** – Install Ansible and set up SSH key-based authentication.  
3. **Test connectivity** – Use `ansible.cfg` and `inventory` to verify connections between Ansible Server and Web Servers.  
4. **Deploy the website** – Run `deploy-jupiter-website.yaml` to install and configure Apache and deploy static content.  
5. **Set up Load Balancer & Domain Name** – Use AWS **ALB** and **Route 53** for traffic management and domain mapping.  
6. **Enable SSL/TLS** – Secure the website with **AWS Certificate Manager**.  

---

## 📖 Step-by-Step Guide  

For detailed steps, check out the **Medium Article**:  
📌 [Deploying a Static Website on AWS with Ansible](https://medium.com/@smaddy799/b8a96d0ca852)  

---

## 💡 Key Features  

✅ **Automated Deployment** – No manual configuration, fully automated using Ansible.  
✅ **High Availability** – Two EC2 Web Servers across different AWS Availability Zones.  
✅ **Scalable & Secure** – ALB for load balancing, Route 53 for domain mapping, and SSL encryption.  



---
