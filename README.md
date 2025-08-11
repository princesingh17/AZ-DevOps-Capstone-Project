# Capstone Project – Azure CI/CD Multistage Pipeline for .NET Application

## 📌 Overview
This Capstone Project demonstrates the end-to-end creation of a **CI/CD Multistage Pipeline** in Azure DevOps to build, test, and deploy a .NET application to **Development (DEV)**, **Pre-Production (PP)**, and **Production (PROD)** environments.  
The project also involves building Azure infrastructure using **Bicep scripts**, implementing **SonarQube code analysis**, setting **release gates**, and configuring **AKS autoscaling**.

---

## ✅ Project Implementation

### **1. Azure DevOps Project Creation**
- Created a new Azure DevOps project named:
      Skillup-Capstone-Project-Prince
  - Configured project settings and repository access.

### **2. Code Setup**
- Pulled the .NET application code from Git.
- Stored and managed the source code in Azure Repos.

### **3. Infrastructure Provisioning**
- Built Azure Kubernetes Service (AKS) clusters for **DEV**, **PP**, and **PROD** environments using **Bicep scripts**.
- Deployed each environment in isolated namespaces.

### **4. Work Item Management**
- Created **Azure Boards tickets**:
- 1 ticket for DEV environment
- 1 ticket for PP environment
- 1 ticket for PROD environment
- Assigned tickets to self for progress tracking.

### **5. Build and Deploy to DEV**
- Configured build pipeline to restore dependencies, build the .NET project, and generate artifacts.
- Deployed the application to the **DEV AKS environment**.

### **6. SonarQube Code Analysis**
- Integrated **SonarQube server** with Azure DevOps.
- Performed **static code analysis** before PP deployment to ensure code quality.

### **7. Release Gates and PROD Deployment**
- Configured **release gates** to enforce quality checks before production release.
- Deployed the application to **PROD AKS environment**.

### **8. AKS Autoscaling**
- Configured **Cluster Autoscaler** to dynamically adjust AKS node count based on load.
- Tested scaling by simulating high/low workloads.

---

## 🧰 Tools & Services Used
- **Azure DevOps** – Repos, Pipelines, Boards
- **Azure Services** – AKS, Resource Groups, Azure Monitor
- **Bicep** – Infrastructure as Code
- **SonarQube** – Code Quality Analysis
- **Kubernetes** – Application Deployment & Scaling

---

## 📚 Learnings
- Creating **multistage pipelines** in Azure DevOps for .NET applications.
- Using **Bicep scripts** to provision Azure infrastructure across multiple environments.
- Managing project tasks and tracking work progress using **Azure Boards**.
- Performing **SonarQube analysis** to ensure code quality before deployment.
- Implementing **release gates** for controlled deployments.
- Configuring and testing **AKS autoscaling** for workload optimization.
- Troubleshooting pipeline and deployment issues in a multi-environment setup.

---

## 📸 Screenshots  
1. Azure DevOps Pipeline Overview.  
2. Successful Deployment to DEV, PP, PROD.    
3. AKS Autoscaling in action.

---

## 📜 Status
**✅ Completed** – Fully functional CI/CD pipeline with automated deployments, quality checks, and AKS autoscaling implemented successfully.

