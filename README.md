# 🚀 Azure Infrastructure as Code | Terraform + GitHub Actions

<p align="center">

<img src="https://img.shields.io/badge/Azure-Cloud-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />

<img src="https://img.shields.io/badge/Terraform-IaC-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />

<img src="https://img.shields.io/badge/GitHub-Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />

<img src="https://img.shields.io/badge/Git-Version%20Control-F05032?style=for-the-badge&logo=git&logoColor=white" />

<img src="https://img.shields.io/badge/Linux-Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />

</p>

<p align="center">

<strong>Production-oriented Azure Infrastructure Automation using Terraform and GitHub Actions</strong>

</p>

---

## 📌 Project Overview

This project demonstrates an **Infrastructure as Code (IaC)** implementation for Microsoft Azure using **Terraform**, with automated CI/CD validation through **GitHub Actions**.

The infrastructure is designed using a **modular Terraform architecture**, allowing reusable components to be deployed across multiple environments such as **Pre-Production** and **Production**.

The GitHub Actions pipeline automates Terraform:

```text
Checkout
   ↓
Terraform Setup
   ↓
Terraform Init
   ↓
Terraform Validate
   ↓
Terraform Plan

CI Pipeline