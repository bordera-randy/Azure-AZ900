# Azure Fundamentals (AZ-900) Labs

## Overview
This repository contains **20 hands-on labs** to help you study for the **Microsoft Azure Fundamentals (AZ-900)** certification. These labs cover key topics such as cloud concepts, core Azure services, security, governance, pricing, and hybrid solutions.

Each lab provides **step-by-step instructions** to help you get practical experience with Azure.

---

## Prerequisites
- **Azure Account**: Sign up for a free Azure account if you don't have one ([Azure Free Account](https://azure.microsoft.com/free/)).
- **Azure Portal Access**: [https://portal.azure.com](https://portal.azure.com)
- **Azure CLI** (optional): Install and configure [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- **Basic Understanding of Cloud Concepts**

---

## Lab 1: Create an Azure Free Account
### Steps:
1. Go to [Azure Free Account](https://azure.microsoft.com/free/).
2. Click **Start Free** and sign in with your Microsoft account.
3. Provide required details and payment information (Azure will not charge for free services).
4. Complete the identity verification process.
5. Access **Azure Portal** at [https://portal.azure.com](https://portal.azure.com).

---

## Lab 2: Deploy a Virtual Machine (VM)
### Steps:
1. Log into the **Azure Portal**.
2. Click **Create a resource** > **Compute** > **Virtual Machine**.
3. Choose an **Image** (e.g., Windows Server 2022 or Ubuntu).
4. Select a **VM size** (e.g., B1s for free-tier eligibility).
5. Configure **Admin username and password**.
6. Set **Public inbound ports** to `Allow RDP (Windows)` or `Allow SSH (Linux)`.
7. Click **Review + Create** and then **Create**.
8. Once deployed, connect to the VM:
   - **Windows VM**: Use Remote Desktop (RDP)
   - **Linux VM**: Use SSH (`ssh <username>@<public-ip>`)

---

## Lab 3: Explore Azure Regions and Availability Zones
### Steps:
1. Open **Azure Portal** > **Create a resource**.
2. Select **Virtual Machine** and view available **Regions**.
3. Choose a region with **Availability Zones** (e.g., East US, West Europe).
4. Under **High availability**, select **Availability Zone**.
5. Deploy a VM in multiple zones for redundancy.

---

## Lab 4: Deploy and Manage Azure Storage
### Steps:
1. In **Azure Portal**, navigate to **Storage Accounts**.
2. Click **Create Storage Account**.
3. Choose a **Resource Group** and enter a **Storage Account Name**.
4. Select a **Region**, **Performance**, and **Redundancy** settings.
5. Click **Review + Create** and then **Create**.
6. Once deployed, go to **Containers**, create a new **Blob Container**, and upload a file.

---

## Lab 5: Configure a Virtual Network (VNet) and Subnets
### Steps:
1. In **Azure Portal**, navigate to **Virtual Networks**.
2. Click **Create a Virtual Network**.
3. Provide **Name**, **Region**, and **Resource Group**.
4. Define **Address Space** (e.g., `10.0.0.0/16`).
5. Add **Subnets** (e.g., `10.0.1.0/24` for VMs, `10.0.2.0/24` for databases).
6. Click **Review + Create** and then **Create**.

---

## Lab 6: Set Up an Azure App Service
### Steps:
1. In **Azure Portal**, navigate to **App Services**.
2. Click **Create App Service**.
3. Select a **Subscription** and **Resource Group**.
4. Enter an **App Name**.
5. Choose **Runtime Stack** (e.g., .NET, Node.js, Python).
6. Select **Pricing Plan** (use Free Tier `F1` if available).
7. Click **Review + Create** and then **Create**.
8. Once deployed, click **Browse** to access the app URL.

---

## Additional Labs
- **Lab 7:** Deploy Azure SQL Database
- **Lab 8:** Set Up Azure Virtual Desktop (AVD)
- **Lab 9:** Implement Azure Role-Based Access Control (RBAC)
- **Lab 10:** Configure Azure Active Directory (Entra ID)
- **Lab 11:** Implement Multi-Factor Authentication (MFA)
- **Lab 12:** Configure Azure Key Vault for Secrets Management
- **Lab 13:** Set Up Azure Policy to Enforce Compliance
- **Lab 14:** Implement Cost Management & Budget Alerts
- **Lab 15:** Configure Azure Monitor & Log Analytics
- **Lab 16:** Deploy a Virtual Machine using an ARM Template
- **Lab 17:** Explore Azure Pricing Calculator
- **Lab 18:** Understand Azure Support Plans & SLAs
- **Lab 19:** Deploy an IoT Hub and Connect a Device
- **Lab 20:** Use Azure Arc to Manage Hybrid Resources

---

## Notes
- Some labs require **Azure CLI** or **PowerShell**, install them if needed.
- Use the **Azure Learn Sandbox** if you want to avoid charges ([Microsoft Learn](https://learn.microsoft.com/en-us/training/)).
- Clean up resources after completing labs to avoid unnecessary costs.

---

## Resources
- [Azure Documentation](https://docs.microsoft.com/en-us/azure/)
- [AZ-900 Exam Guide](https://learn.microsoft.com/en-us/certifications/exams/az-900/)
- [Microsoft Learn](https://learn.microsoft.com/en-us/training/)

Happy learning! 🚀
