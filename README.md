# Red-Hat-System-Administration-III-Linux-Automation




This repository contains Ansible-based automation lab exercises completed as part of the Red Hat System Administration III (RH294) course. The labs focus on automating Linux system configurations and services using Red Hat Enterprise Linux and Ansible best practices.

---

## 📘 Overview
The labs included in this report demonstrate:
- Playbook execution using `ansible-navigator`
- Modular playbook design and reuse
- Service configuration (firewall, HTTPD, MariaDB, SSL)
- Automation using Red Hat System Roles
- Security with Ansible Vault
- Review labs and grading checks across multi-host environments

---

## 📂 Lab Summary

| Lab Name              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `internet.yml`       | Configures firewall, web, and database services                             |
| `diagnose.yml`       | Troubleshoots SSL/HTTPS configuration errors                                |
| `control-review.yml` | Validates running web and database services with secure configuration      |
| `banner.yml`         | Deploys login warning banners via Ansible playbook                          |
| `project-review.yml` | Automates user creation, banner setup, and service enablement across nodes |
| `role-review.yml`    | Demonstrates reusable roles for user and content deployment                 |
| `system-review.yml`  | Uses system roles to automate storage, network, and user configuration      |
| `review-cr1` → `cr4` | Full-stack service deployment and validation across 4 machines              |

---

## 🧠 Key Features
- 🔐 **Ansible Vault**: Encrypting sensitive variables and credentials
- 📦 **Roles**: Use of `ansible-galaxy init` to create custom roles
- 🧰 **Red Hat System Roles**: Leveraging RHEL-provided roles for SELinux, storage, network, etc.
- 🐳 **Podman/EEs**: Execution within isolated environments
- 📡 **Ansible Navigator**: Interactive playbook execution with feedback loop

---

## 📄 Report Contents
This repository includes screenshots and structured execution results:
- Step-by-step playbook validation and execution
- End-of-Chapter Labs and Comprehensive Review
- Grading script results showing real-time lab pass/fail states

---

## 👨‍💻 Author
**Sanjay Devang**  
Graduate Student, George Washington University  
Email: s.devang@email.gwu.edu

---

## ✅ Completion Status
All labs executed successfully with full grading script validation, as demonstrated in the included rep
