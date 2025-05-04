# ITIOPS: CLOUDSUITEx - DEPLOYMENT

---

> **Team:** ITIOPS
> ---
> **Project:** CLOUDSUITEx - DEPLOYMENT

---

## ✨ Collaborators 

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/hosseldin" width="100px;" alt="hosseldin"/><br />
      <a href="https://github.com/hosseldin"><sub><b>Hossam Mahmoud</b></sub></a><br />
      <a href="https://www.linkedin.com/in/hossammahmoudatta/">LinkedIn</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/mina-safwat-1" width="100px;" alt="mina-safwat-1"/><br />
      <a href="https://github.com/mina-safwat-1"><sub><b>Mina Safwat</b></sub></a><br />
      <a href="https://www.linkedin.com/in/mina-safwat5/">LinkedIn</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/M-Samii" width="100px;" alt="M-Samii"/><br />
      <a href="https://github.com/M-Samii"><sub><b>Mahmoud Samy</b></sub></a><br />
      <a href="https://www.linkedin.com/in/mahmoud-samy-301b0b196/">LinkedIn</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/Mohamed0Mourad" width="100px;" alt="Mohamed0Mourad"/><br />
      <a href="https://github.com/Mohamed0Mourad"><sub><b>Mohammed Mourad</b></sub></a><br />
      <a href="https://www.linkedin.com/in/mohamed-0mourad/">LinkedIn</a>
    </td>
  </tr>
</table>

</div>

---

### 🔗 Related Repositories

- [💻 Application Source Code](https://github.com/hosseldin/ITIOPS.CLOUDSUITEx-APPLICATION)
- [🛠 Infrastructure Repo](https://github.com/hosseldin/ITIOPS.CLOUDSUITEx-INFRASTRUCTURE)
- [🚀 Deployment Manifests (GitOps)](https://github.com/mina-safwat-1/ITIOPS.CLOUDSUITEx-DEPLOYMENT)

---

## 🚀 Project Overview

**Objective:** Provision and deploy a secure AWS infrastructure and CI/CD pipeline. Deploy a Node.js web application with MySQL and Redis, integrate security scanning, and set up monitoring and alerting.

**Key Features:**

* Infrastructure as Code with Terraform
* Continuous Integration with Jenkins
* GitOps-driven Continuous Delivery via ArgoCD & Argo Image Updater
* Secrets Management using External Secrets Operator & AWS Secrets Manager
* Security Scanning with Trivy
* Monitoring & Visualization using Prometheus & Grafana
* Ingress & HTTPS using Amazon Route 53 and AWS Certificate Manager (ACM)

---

## 🏗 Architecture Diagram

![Architecture Diagram](itiops-diag.png)

---

# 🚀 Node.js Connectivity Checker App

This is a lightweight Node.js application that provides simple web endpoints to test connectivity to **MySQL** and **Redis** services. It's ideal for CI/CD pipeline testing, container health checks, or service validation in Kubernetes environments.

---

## 📦 Features

- ✅ `/db` route to test **MySQL** connection
- ✅ `/redis` route to test **Redis** connectivity
- 🌐 Returns simple HTML responses for easy browser checking
- ⚙️ Uses environment variables for all connection settings

---

## 🔧 Environment Variables

Before running the app, set the following environment variables:

### For MySQL

| Variable           | Description                  |
|--------------------|------------------------------|
| `MYSQL_HOSTNAME`   | Hostname of the MySQL server |
| `MYSQL_USER`       | MySQL username               |
| `MYSQL_PASSWORD`   | MySQL password               |
| `MYSQL_PORT`       | (Optional) MySQL port (default: `3306`) |

### For Redis

| Variable           | Description                  |
|--------------------|------------------------------|
| `REDIS_HOSTNAME`   | Hostname of the Redis server |
| `REDIS_PORT`       | (Optional) Redis port (default: `6379`) |

---

## 🚀 How to Run

### Locally

```bash
# Install dependencies
npm install
```

# Run the app with environment variables
MYSQL_HOSTNAME=localhost \
MYSQL_USER=root \
MYSQL_PASSWORD=pass \
REDIS_HOSTNAME=localhost \
node app.js

---

*Developed with ❤️ by ITIOPS Team*

## ✨ Collaborators 

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/hosseldin" width="100px;" alt="hosseldin"/><br />
      <a href="https://github.com/hosseldin"><sub><b>Hossam Mahmoud</b></sub></a><br />
      <a href="https://www.linkedin.com/in/hossammahmoudatta/">LinkedIn</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/mina-safwat-1" width="100px;" alt="mina-safwat-1"/><br />
      <a href="https://github.com/mina-safwat-1"><sub><b>Mina Safwat</b></sub></a><br />
      <a href="https://www.linkedin.com/in/mina-safwat5/">LinkedIn</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/M-Samii" width="100px;" alt="M-Samii"/><br />
      <a href="https://github.com/M-Samii"><sub><b>Mahmoud Samy</b></sub></a><br />
      <a href="https://www.linkedin.com/in/mahmoud-samy-301b0b196/">LinkedIn</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/Mohamed0Mourad" width="100px;" alt="Mohamed0Mourad"/><br />
      <a href="https://github.com/Mohamed0Mourad"><sub><b>Mohammed Mourad</b></sub></a><br />
      <a href="https://www.linkedin.com/in/mohamed-0mourad/">LinkedIn</a>
    </td>
  </tr>
</table>

</div>


<br>
