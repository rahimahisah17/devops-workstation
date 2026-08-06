# 🖥️ DevOps Workstation Setup

<p align="center">

![Platform](https://img.shields.io/badge/Platform-Windows_11-0078D4?style=for-the-badge&logo=windows)
![Git](https://img.shields.io/badge/Git-Installed-F05032?style=for-the-badge&logo=git&logoColor=white)
![Azure CLI](https://img.shields.io/badge/Azure_CLI-Installed-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Installed-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-Installed-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-Ready-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</p>

---

## 📖 Overview

A properly configured workstation is the foundation of every successful DevOps engineer.

This repository documents the installation and verification of essential DevOps tools required for cloud engineering, Infrastructure as Code (IaC), containerization, source control, and cloud automation.

The objective is to build a professional development environment capable of supporting modern DevOps workflows.

---

# 🛠️ Tools Verified

| Tool | Purpose | Status |
|------|---------|--------|
| Git | Version Control | ✅ Installed |
| Azure CLI | Azure Management | ✅ Installed |
| Docker Desktop | Containerization | ✅ Installed |
| Terraform | Infrastructure as Code | ✅ Installed |
| Visual Studio Code | Development Environment | ✅ Installed |

---

# 🔍 Version Verification

The following commands were used to verify each installation.

## Git

```bash
git --version
```

Example Output

```text
git version 2.x.x.windows.x
```

---

## Azure CLI

```bash
az version
```

Example Output

```text
azure-cli                         x.x.x
```

---

## Docker

```bash
docker --version
```

Example Output

```text
Docker version xx.x.x
```

---

## Terraform

```bash
terraform version
```

Example Output

```text
Terraform v1.x.x
```

---

## Visual Studio Code

```bash
code --version
```

Example Output

```text
1.xx.x
```

---

# 🚀 How These Tools Contribute to DevOps

## 🌿 Git — Source Control Management

### DevOps Role

Version Control & Single Source of Truth

### Contribution

Git forms the backbone of modern DevOps practices by providing version control, collaboration through branching strategies, and complete change history.

It also enables Infrastructure as Code (IaC) repositories to trigger automated CI/CD pipelines whenever changes are committed.

---

## ☁️ Azure CLI — Cloud Automation

### DevOps Role

Command-Line Cloud Management

### Contribution

Azure CLI replaces manual portal operations with automation.

Engineers can provision, manage, monitor, and audit Azure resources directly from the command line, making deployments repeatable and ideal for scripting and CI/CD workflows.

---

## 🐳 Docker — Containerization

### DevOps Role

Environment Consistency & Isolation

### Contribution

Docker packages applications together with their dependencies into lightweight containers, ensuring applications run consistently across development, testing, and production environments.

This eliminates the classic "works on my machine" problem.

---

## 🏗️ Terraform — Infrastructure as Code

### DevOps Role

Declarative Infrastructure Provisioning

### Contribution

Terraform enables infrastructure to be defined using code rather than manual configuration.

Infrastructure becomes version-controlled, repeatable, and easily reproducible, reducing configuration drift and improving deployment reliability.

---

## 💻 Visual Studio Code — Development Workspace

### DevOps Role

Unified Engineering Interface

### Contribution

Visual Studio Code serves as the central workspace for DevOps engineers by integrating:

- Source Control
- Integrated Terminal
- Docker Extension
- Terraform Extension
- Azure Extensions
- Debugging Tools

This creates a streamlined development experience for building and managing cloud-native applications.

---

# 🎯 DevOps Workflow

```text
                Write Code
                     │
                     ▼
              Git Version Control
                     │
                     ▼
              GitHub Repository
                     │
                     ▼
              CI/CD Pipeline
                     │
        ┌────────────┼────────────┐
        ▼                         ▼
 Terraform                  Docker Build
        │                         │
        ▼                         ▼
 Azure Infrastructure      Container Image
        │                         │
        └────────────┬────────────┘
                     ▼
              Cloud Deployment
```

---

# 📂 Repository Structure

```text
devops-workstation-setup/
│
├── README.md
├── screenshots/
│   ├── git-version.png
│   ├── azure-cli-version.png
│   ├── docker-version.png
│   ├── terraform-version.png
│   └── vscode-version.png
└── LICENSE
```

---

# 🎯 Key Skills Demonstrated

- Git Version Control
- Cloud CLI Administration
- Docker Containerization
- Infrastructure as Code (Terraform)
- Azure Automation
- DevOps Environment Setup
- Developer Productivity Tools
- Command-Line Operations

---

# 📚 Technologies

- Git
- Azure CLI
- Docker
- Terraform
- Visual Studio Code
- Windows 11

---

# 👩‍💻 Author

**Rahimah Isah**

Cloud Engineer | DevOps Engineer | Microsoft Azure

GitHub: https://github.com/rahimahisah17

---

## ⭐ If you found this repository helpful, consider giving it a star!
