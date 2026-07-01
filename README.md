# 🚀 ServiceNow Virtual Internship & Employee Onboarding Automation

> Completed as part of the **ServiceNow Virtual Internship Program** by ServiceNow University, AICTE, and SmartBridge — with a hands-on implementation project built using **App Engine Studio**.

---

## 📋 Table of Contents

- [Internship Program](#-internship-program)
- [Project Overview](#-project-overview)
- [Features](#-features)
- [Application Architecture](#-application-architecture)
- [Project Workflow](#-project-workflow)
- [Technologies Used](#-technologies-used)
- [Screenshots](#-screenshots)
- [Author](#-author)

---

## 🎓 Internship Program

**Certificate of Completion** — ServiceNow Virtual Internship Program

### Key Learning Areas

| Area | Description |
|---|---|
| ServiceNow Administration | Platform fundamentals & navigation |
| Agentic AI | Introduction to AI-driven automation |
| Flow Designer | Building automated workflows |
| ATF | Automated Test Framework |
| Reporting & Analytics | Dashboards and data insights |
| CSA Prep | Certified System Administrator readiness |

### Skills Acquired

- ✅ ServiceNow Platform Navigation
- ✅ Application Development using App Engine Studio
- ✅ Table and Form Configuration
- ✅ Flow Automation & Workflow Design
- ✅ Role-Based Access Control & Security
- ✅ Data Management

---

## 📦 Project Overview

**Project:** Employee Onboarding Automation System

The goal of this project is to **automate the employee onboarding process** using native ServiceNow capabilities — with zero custom scripting.

Users submit onboarding requests via a structured form. The system automatically triggers an approval workflow via Flow Designer and updates the request status without any manual intervention.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🏗️ Custom Application | Built entirely in App Engine Studio |
| 🗄️ Data Management | Custom Employee Request table with structured fields |
| 📝 Form Design | User-friendly onboarding request form |
| 🔐 Security | Admin and User roles with controlled access |
| ⚙️ Workflow Automation | Flow Designer trigger on record creation |
| ✔️ Tested | End-to-end flow execution validated successfully |

---

## 🏛️ Application Architecture

```
User
 │
 ▼
Employee Onboarding Form
 │
 ▼
Employee Request Table
 │
 ▼
Flow Designer Trigger
(On: Record Created)
 │
 ▼
Update Record Action
(Status: Requested → Approved)
 │
 ▼
Updated Request Record ✅
```

> 📁 Architecture diagram available at: `Assets/Architecture_Diagram.png`

---

## 🔄 Project Workflow

1. **Submit** — User fills and submits the onboarding request form
2. **Store** — Request is saved in the Employee Request table
3. **Detect** — Flow Designer detects the new record creation
4. **Execute** — Automated workflow runs without manual input
5. **Update** — Request status changes from `Requested` → `Approved`
6. **Persist** — Updated record is stored on the platform

---

## 🛠️ Technologies Used

- ServiceNow App Engine Studio
- Flow Designer
- ServiceNow Data Tables & Forms
- Role-Based Access Control (RBAC)
- Workflow Automation (No-Code)

---

## 📸 Screenshots

The `Screenshots/` folder includes:

- Application Home
- Table Configuration
- Form Design
- Flow Designer Setup
- Successful Flow Execution
- Sample Test Records

---

## 👤 Author

**Shaik Afrin**
Student | ServiceNow Learner | Aspiring Software Engineer
