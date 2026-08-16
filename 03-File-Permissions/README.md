# 🔐 Project 03 — Linux File Permissions & Access Control

## 🎯 Project Overview

### What

I built and secured a simulated company Linux environment on **Rocky Linux** by configuring users, groups, file ownership, permissions, ACLs, and Linux special permissions.

The environment was designed around three IT roles:

| User | Role | Group |
|---|---|---|
| `alice` | Linux Administrator | `linuxadmins` |
| `bob` | Developer | `developers` |
| `charlie` | Security Auditor | `auditors` |

I created department-specific directories and files, then configured access based on each user's responsibilities.

### Why

The purpose of this project was to practice how a Linux Systems Administrator controls access to company resources while following the **principle of least privilege**.

Instead of giving every user full access, each user was given only the permissions required for their role.

I also intentionally created permission problems, tested unauthorized access, and troubleshot the resulting `Permission denied` errors.

### How

I used native Linux administration tools and concepts including:

- `chmod`
- `chown`
- `chgrp`
- `setfacl`
- `getfacl`
- Linux users and groups
- File and directory ownership
- Read, write, and execute permissions
- ACLs
- SUID
- SGID
- Sticky Bit
- Permission troubleshooting
- User access testing

---

# 🏢 Real-World IT Scenario

I approached this project as a **Junior Linux Systems Administrator** responsible for securing resources on a company Linux server.

The company has three IT roles:

| User | Role | Group |
|---|---|---|
| `alice` | Linux Administrator | `linuxadmins` |
| `bob` | Developer | `developers` |
| `charlie` | Security Auditor | `auditors` |

Each department has its own resources, and permissions were configured according to each user's responsibilities.

### Access-Control Goals

- **Alice** → Administrative resources
- **Bob** → Development resources
- **Charlie** → Auditing resources
- **IT users** → Shared collaboration directory
- **Unauthorized users** → Access denied

The goal was to follow the principle of least privilege and ensure users could access only the resources required for their responsibilities.

---

# 📁 Project Structure

```text
/company
├── administration
│   └── server-notes.txt
│
├── auditing
│   └── security-report.txt
│
├── development
│   └── app-notes.txt
│
└── shared
    └── team-notes.txt
