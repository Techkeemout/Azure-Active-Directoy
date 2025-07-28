# Azure AD Hybrid Identity & Security Lab  
### for **Northwind Innovations Inc.**

![Azure Logo](https://seeklogo.com/images/M/microsoft-azure-logo-77619ADE26-seeklogo.com.png)

## Fictitious Company Overview

**Northwind Innovations Inc.** is a mid-sized SaaS company that provides AI-powered supply chain analytics solutions. As part of a digital transformation initiative, the company is migrating from an on-premises Active Directory to a hybrid cloud environment using **Azure Active Directory (Azure AD)** and related Microsoft security and governance tools.

This lab simulates real-world identity, access, and security scenarios in **cloud and hybrid environments**.

---

## Project Scope

This lab covers:

- Azure AD Cloud & Hybrid Identity Management
- Authentication & Access Controls
- Identity Governance & Protection
- Privileged Access Management (PIM)
- Azure Policies & Governance
- Network, Perimeter & Host Security
- Azure Firewall Deployment

Each section includes PowerShell scripts, configuration files, screenshots, and documentation.

---

## Lab Architecture Overview

---

## 📁 Lab Modules

### 01.  Users & Groups (Cloud + Hybrid)
- Create cloud-only users via PowerShell
- Sync on-prem users via Azure AD Connect
- Assign users to security and Microsoft 365 groups

📂 [`/01-users-groups`](./01-users-groups)

---

### 02.  Authentication Management
- Enable Multi-Factor Authentication (MFA)
- Configure Conditional Access policies
- Set up Self-Service Password Reset (SSPR)
- Allow secure guest access (B2B)

📂 [`/02-authentication`](./02-authentication)

---

### 03. Identity Protection & Governance
- Deploy Azure AD Identity Protection
- Configure risk-based Conditional Access
- Set up Access Reviews and lifecycle workflows

📂 [`/03-identity-protection`](./03-identity-protection)

---

### 04. Privileged Identity Management (PIM)
- Just-in-time (JIT) role activation
- Time-limited and approval-based admin roles
- Audit and alerts for privileged activity

📂 [`/04-pim`](./04-pim)

---

### 05. Azure Policies & Governance
- Enforce allowed locations
- Apply mandatory tags to resources
- Implement compliance initiatives and Blueprints

📂 [`/05-policies`](./05-policies)

---

### 06. Network, Host & Container Security
- Configure NSGs and Just-In-Time VM access
- Enable Microsoft Defender for VMs and AKS
- Scan container images for vulnerabilities

📂 [`/06-security`](./06-security)

---

### 07. Azure Firewall Deployment
- Deploy Azure Firewall in hub network
- Configure rules for outbound and inbound access
- Integrate with Azure Monitor logs

📂 [`/07-firewall`](./07-firewall)

---

##  Tools & Technologies

| Category                | Tools / Services                   |
|------------------------|------------------------------------|
| Identity               | Azure AD, AD Connect, PIM          |
| Security               | Azure Defender, Conditional Access |
| Governance             | Azure Policy, Blueprints           |
| Networking             | NSGs, Azure Firewall, VPN Gateway  |
| Automation             | PowerShell, ARM/Bicep, Azure CLI   |
| Containers             | AKS, ACR, Defender for Containers  |

---

## Goals & Learning Outcomes

By completing this lab, you will learn to:

- Design and implement hybrid identity with Azure AD
- Manage secure authentication and access
- Apply identity governance and risk-based policies
- Secure infrastructure using layered network and perimeter defenses
- Automate role assignment and access control using PIM
- Apply real-world security best practices in a cloud-native environment

---

## Notes

- All configurations in this lab are for demonstration and educational purposes.
- Be cautious when enabling global security policies in real environments.

---

## 📧 Contact / Credits

Created by Rakeem 
GitHub: https://github.com/Techkeemout
LinkedIn: https://www.linkedin.com/in/rakeemdawson/

---
