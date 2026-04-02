# CC-Practicals
Here's the raw markdown you can paste directly into your GitHub README:

```markdown
# ☁️ Cloud Platforms – Getting Started Guide

> A beginner-friendly walkthrough to setting up free-tier accounts on **AWS**, **Azure**, and **GCP**, exploring their core services, and understanding pricing tools.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Part 1 – Create Free-Tier Accounts](#part-1--create-free-tier-accounts)
- [Part 2 – Explore Dashboards & Key Services](#part-2--explore-dashboards--key-services)
- [Part 3 – Understand Pricing Calculators](#part-3--understand-pricing-calculators)
- [Quick Comparison](#quick-comparison)
- [Next Steps](#next-steps)

---

## Overview

This guide helps you get hands-on with the three major cloud platforms. By the end, you will have:

- Active free-tier accounts on AWS, Azure, and GCP
- Familiarity with each platform's management console
- An understanding of core service categories: compute, storage, and networking
- Experience using each platform's pricing calculator

No prior cloud experience is required.

---

## Part 1 – Create Free-Tier Accounts

### Amazon Web Services (AWS)

1. Visit [https://aws.amazon.com/free](https://aws.amazon.com/free)
2. Click **Create a Free Account**
3. Enter your email address and choose an AWS account name
4. Provide billing information (a credit card is required, but you will not be charged within free-tier limits)
5. Complete identity verification via phone
6. Select the **Basic Support – Free** plan

**What you get (12-month free tier highlights):**
- 750 hours/month of EC2 t2.micro or t3.micro instances
- 5 GB of S3 standard storage
- 750 hours/month of RDS (single-AZ db.t2.micro)
- 1 million Lambda requests/month (always free)

---

### Microsoft Azure

1. Visit [https://azure.microsoft.com/free](https://azure.microsoft.com/free)
2. Click **Start free**
3. Sign in with or create a Microsoft account
4. Provide billing information
5. Complete identity verification

**What you get:**
- $200 USD credit valid for 30 days
- 12 months of popular free services (e.g., 750 hours of B1s VMs, 5 GB Blob Storage)
- 55+ services that are always free (e.g., Azure Functions, Azure DevOps)

---

### Google Cloud Platform (GCP)

1. Visit [https://cloud.google.com/free](https://cloud.google.com/free)
2. Click **Get started for free**
3. Sign in with a Google account
4. Provide billing information

**What you get:**
- $300 USD credit valid for 90 days
- Always-free tier including 1 f1-micro VM instance per month, 5 GB of Cloud Storage, and 1 million Cloud Functions invocations/month

---

> ⚠️ **Note:** All three platforms require a valid credit card for identity verification. You will only be charged if you exceed free-tier limits or explicitly upgrade your account.

---

## Part 2 – Explore Dashboards & Key Services

Once your accounts are active, spend time navigating each console. Below are the key service categories and where to find them.

---

### 🖥️ Compute

Compute services let you run applications in the cloud.

| Platform | Service Name | Console Location |
|---|---|---|
| AWS | EC2 (Elastic Compute Cloud) | Services → Compute → EC2 |
| Azure | Virtual Machines | Home → Virtual Machines |
| GCP | Compute Engine | Navigation Menu → Compute Engine |

**What to look for:**
- Instance/VM types and sizes (e.g., t2.micro on AWS, B1s on Azure, e2-micro on GCP)
- How to launch, stop, and terminate instances
- Regions and availability zones

---

### 🗄️ Storage

Storage services let you save files, objects, and data in the cloud.

| Platform | Service Name | Console Location |
|---|---|---|
| AWS | S3 (Simple Storage Service) | Services → Storage → S3 |
| Azure | Blob Storage | Home → Storage Accounts |
| GCP | Cloud Storage | Navigation Menu → Cloud Storage |

**What to look for:**
- How to create a bucket or storage container
- Storage classes (e.g., Standard, Infrequent Access, Archive)
- Access control and permissions

---

### 🌐 Networking

Networking services control how your resources communicate.

| Platform | Service Name | Console Location |
|---|---|---|
| AWS | VPC (Virtual Private Cloud) | Services → Networking → VPC |
| Azure | Virtual Network (VNet) | Home → Virtual Networks |
| GCP | VPC Network | Navigation Menu → VPC Network |

**What to look for:**
- How to create a virtual network
- Subnets, IP ranges, and routing
- Security groups / firewall rules

---

### 💡 Tips for Exploring Dashboards

- Use the **search bar** at the top of each console to quickly find any service
- Check the **"Getting Started"** or **"Quickstart"** sections within each service
- Enable **Cost Alerts / Budgets** immediately to avoid unexpected charges:
  - AWS: Billing Dashboard → Budgets
  - Azure: Cost Management → Budgets
  - GCP: Billing → Budgets & Alerts

---

## Part 3 – Understand Pricing Calculators

Each platform provides a pricing calculator to estimate costs before you deploy anything.

---

### AWS Pricing Calculator

🔗 [https://calculator.aws/pricing/2/home](https://calculator.aws/pricing/2/home)

**How to use it:**
1. Click **Create estimate**
2. Search for a service (e.g., EC2)
3. Configure your expected usage (region, instance type, hours/month)
4. Add multiple services to build a full estimate
5. Click **Export** to save or share your estimate

**Key features:**
- Supports 100+ services
- Allows grouped estimates by project or team
- Exportable as CSV or shareable via URL

---

### Azure Pricing Calculator

🔗 [https://azure.microsoft.com/pricing/calculator](https://azure.microsoft.com/pricing/calculator)

**How to use it:**
1. Browse or search for a product (e.g., Virtual Machines)
2. Configure options: region, OS, tier, hours
3. View the monthly cost estimate on the right panel
4. Click **Save** or **Export** to keep your estimate

**Key features:**
- Side-by-side comparison of tiers (Basic, Standard, Premium)
- Dev/Test pricing options
- Supports saving estimates to your Azure account

---

### GCP Pricing Calculator

🔗 [https://cloud.google.com/products/calculator](https://cloud.google.com/products/calculator)

**How to use it:**
1. Select a product (e.g., Compute Engine)
2. Fill in the configuration fields (machine type, region, hours)
3. The cost estimate updates in real time on the right
4. Click **Add to Estimate** for multiple services
5. Share or export the final estimate

**Key features:**
- Real-time cost updates as you configure
- Sustained-use discounts calculated automatically
- Shareable via link

---

### 📊 Calculator Comparison

| Feature | AWS | Azure | GCP |
|---|---|---|---|
| Real-time updates | Partial | Yes | Yes |
| Shareable link | Yes | Yes | Yes |
| Export to CSV | Yes | Yes | No (PDF only) |
| Dev/Test pricing | Yes | Yes | No |
| Sustained use discounts | Manual | Manual | Automatic |

---

## Quick Comparison

| | AWS | Azure | GCP |
|---|---|---|---|
| Free credit | None | $200 / 30 days | $300 / 90 days |
| Always-free tier | Yes (broad) | Yes (55+ services) | Yes (selected services) |
| Console complexity | Moderate | Moderate | Beginner-friendly |
| Best for | General cloud | Microsoft/enterprise ecosystem | Data & ML workloads |

---

## Next Steps

After completing the above, consider exploring:

- **Serverless computing:** AWS Lambda, Azure Functions, GCP Cloud Functions
- **Managed databases:** AWS RDS, Azure SQL Database, GCP Cloud SQL
- **Identity & Access Management (IAM):** Learn how to create users, roles, and policies on each platform
- **Cloud CLI tools:** AWS CLI, Azure CLI (`az`), GCP SDK (`gcloud`)
- **Infrastructure as Code:** Terraform (works across all three platforms)

---

## Resources

- [AWS Documentation](https://docs.aws.amazon.com)
- [Azure Documentation](https://learn.microsoft.com/azure)
- [GCP Documentation](https://cloud.google.com/docs)
- [AWS Free Tier FAQ](https://aws.amazon.com/free/faqs/)
- [Azure Free Account FAQ](https://azure.microsoft.com/free/free-account-faq/)
- [GCP Free Tier Details](https://cloud.google.com/free/docs/free-cloud-features)

---

Just copy everything inside the code block and paste it into your `README.md` file on GitHub. It'll render with all the headers, tables, and links properly formatted.
