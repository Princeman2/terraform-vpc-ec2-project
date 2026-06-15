# Terraform VPC + EC2 Infrastructure as Code Project

**Automated provisioning of AWS VPC and EC2 instance using Terraform**

![Terraform Apply](terraform-apply.png)

---

## 📋 Project Summary

This project demonstrates **Infrastructure as Code (IaC)** by using **Terraform** to automatically create a basic network (VPC) and a web server (EC2 instance) on AWS Free Tier.

**Objective**: Replace manual clicking in the AWS Console with reusable, version-controlled code.

---

## 🎯 Project Objectives & Fulfillment

| Objective                                | How It Was Achieved |
|------------------------------------------|---------------------|
| Provision basic network + web server using code | Created VPC, Subnet & EC2 using Terraform |
| Learn Infrastructure as Code             | Wrote declarative `main.tf` configuration |
| Practice full Terraform workflow         | Executed init, plan, apply, and state management |
| Understand resource dependencies         | Properly linked VPC → Subnet → EC2 |
| Maintain zero cost                       | Used only Free Tier + planned to destroy |

---

## 🛠️ Technologies Used

- Terraform (IaC)
- AWS (VPC, EC2 t3.micro)
- Git & GitHub

---

## 📸 Project Screenshots

### 1. Terraform Apply Success
![Terraform Apply](terraform-apply.png)

### 2. EC2 Instance Running
![EC2 Instance](ec2-instance.png)

### 3. AWS VPC Created
![VPC](vpc.png)

### 4. Terraform Plan Output
![Terraform Plan](terraform-plan.png)

### 5. Terraform State List
![Terraform State](terraform-state.png)

---

## 🧩 What I Implemented

- Clean Terraform configuration with proper tagging
- Resource dependency management
- Full lifecycle demonstration (create → verify → destroy)

---

## 💡 Skills Demonstrated

- Infrastructure as Code principles
- Terraform workflow (`init`, `plan`, `apply`, `state`)
- AWS networking basics
- Clean documentation with visual proof

---

## 📂 Project Structure
