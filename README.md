# 🏛️ Birzeit Municipality Archiving System (BMAS)

> A secure, intelligent, and role-based digital archiving platform designed to modernize document management for municipal organizations.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge\&logo=flask\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![GraphDB](https://img.shields.io/badge/GraphDB-FF6F00?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)

---

## 📋 Overview

The Birzeit Municipality Archiving System (BMAS) was developed to replace inefficient manual document management systems such as Excel sheets, Word documents, and paper-based records.

These traditional systems often resulted in document loss, poor classification, and time inefficiency.
BMAS provides a centralized digital solution that enables secure, efficient, and intelligent document storage and retrieval.

---

## ✨ Key Features

* 🔎 **Semantic Search** — Retrieve documents based on meaning and context using SPARQL and RDF
* 🔐 **Role-Based Access Control (RBAC)** — Structured permissions for different user roles
* 📄 **Document Archiving Workflow** — Metadata entry, validation, and approval process
* 🔄 **Version Control** — Maintain history and previous document versions
* 🏷️ **Dynamic Metadata Management** — Flexible metadata schemas per category
* 📊 **Reporting System** — Generate reports with filtering and export capabilities
* 🗂️ **Department & Category Management** — Organized hierarchical structure
* 📝 **Audit Logging** — Track all system activities
* 🔒 **Secure Authentication** — Password hashing and protected access

---

## 👩‍💻 My Contribution

* Developed backend functionality using **Flask (Python)**
* Designed and implemented **MySQL database schema**
* Built **semantic search using GraphDB, RDF, and SPARQL**
* Implemented **role-based access control system**
* Contributed to **frontend UI and user experience**

---

## 👥 User Roles

| Role | Permissions |
|------|------------|
| 🛡️ Administrative Affairs | Full access — user management, approvals, audit logs, reports, metadata schemas |
| 👔 Department Head | Approve documents, manage department documents, generate reports |
| 👷 Municipal Employee | Archive, search, view, and edit their own documents (with approval flow) |
| 🗝️ Secretary | View and search documents only |

---

## 🛠️ Tech Stack

### 🎨 Frontend
| Tool | Purpose |
|------|---------|
| Figma | UI/UX Design & Prototyping |
| HTML5 & CSS3 | Structure & Styling |
| JavaScript | Interactivity, form validation, dynamic content |

### ⚙️ Backend
| Tool | Purpose |
|------|---------|
| Python | Core backend logic |
| Flask | Web framework, routing & HTTP handling |

### 🗄️ Database & Storage
| Tool | Purpose |
|------|---------|
| MySQL (via XAMPP) | Structured data — users, documents, metadata, audit logs |
| GraphDB | Semantic search via RDF triples and SPARQL queries |
| Local File Storage | PDF document storage with unique timestamped filenames |

### 🔧 Dev Tools
| Tool | Purpose |
|------|---------|
| VS Code | Primary IDE |
| GitHub | Version control & team collaboration |
| Postman | API testing |
| pytest & Flask Test Client | Backend unit & integration testing |
| MySQL Workbench | Database verification |
| GraphDB Workbench | RDF triple validation |


---

## 🏗️ Architecture

The system follows a **4-tier architecture**:
```
┌─────────────────────────────┐
│     Presentation Layer      │  HTML, CSS, JavaScript
├─────────────────────────────┤
│    Business Logic Layer     │  Python, Flask (modular routes)
├─────────────────────────────┤
│   Domain & Utilities Layer  │  RBAC, DB helpers, semantic indexing
├─────────────────────────────┤
│       Database Layer        │  MySQL + GraphDB + File Storage
└─────────────────────────────┘
```
---

## 📸 Screenshots

### 🔑 Authentication

| Login                           | 
| ------------------------------- |
| ![Login](screenshots/login.png) |

| create new account by the adminstrative affairs  |
|  ----------------------------------------------- |
| ![create new account by the adminstrative affairs](screenshots/createnewacc.png) |

| Approve/Reject requests          |
| -------------------------------  |
| ![approval](screenshots/approvals.png)  |

### 🏠 Dashboards

| Admin Dashboard                           |
| ----------------------------------------- |
| ![Admin](screenshots/dashboard.png) |

| RBAC                                      |
| ----------------------------------------- |
| ![rbac](screenshots/RBAC.png)       |

### 📂 Core Features

| View Documents                          |
| --------------------------------------- |
| ![View](screenshots/viewdocs.png) | ![View](screenshots/viewdocs2.png) |

| Semantic Search                   |
| --------------------------------- |
| ![Search](screenshots/search.png) |


| Archive                             | 
| ----------------------------------- | 
| ![Archive](screenshots/step1archive.png) | ![Archive](screenshots/step2archive(a).png) | ![Archive](screenshots/step2archive(b).png) | ![Archive](screenshots/step2archive(c).png) |

| metadata                          |
| --------------------------------- |
| ![metadata](screenshots/metadata.png) |


| Department and category management  |
| ----------------------------------- |
| ![Reports](screenshots/depandcatmanage.png) |


| Reports                             |
| ----------------------------------- |
| ![Reports](screenshots/generatereport.png) |


---

## 📚 Project Context

This project was developed as a: **Graduation Project**
Developed collaboratively as a team project.

---

## ⭐ Key Highlights

* Full-stack system design
* Real-world problem solving
* Integration of semantic technologies (RDF & SPARQL)
* Secure and scalable architecture
