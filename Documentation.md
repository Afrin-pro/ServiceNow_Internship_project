# Employee Onboarding Automation System

## Application Information

Application Name:
Employee Onboarding

Platform:
ServiceNow App Engine Studio

Development Approach:
Low-Code / No-Code

---

## Business Problem

Organizations often manage onboarding activities manually, resulting in delays and inconsistent processing.

The objective of this application is to automate onboarding request handling using ServiceNow workflow automation.

---

## Solution Overview

The solution consists of:

* Employee onboarding request form
* Employee request database table
* Security roles
* Automated approval workflow

---

## Data Model

### Table

Employee Request

### Fields

| Field Name      | Type          |
| --------------- | ------------- |
| Employee Name   | String        |
| Employee Email  | String        |
| Employee ID     | String        |
| Department      | Choice        |
| Manager Name    | String        |
| Joining Date    | Date/Time     |
| Laptop Required | True/False    |
| Status          | Choice        |
| Comments        | Journal Input |

---

## Security Model

### Admin Role

Permissions:

* Create
* Read
* Update
* Delete

### User Role

Permissions:

* Create
* Read

---

## Flow Design

Flow Name:
Employee Onboarding Approval Flow

### Trigger

Record Created

Table:
Employee Request

### Action

Update Record

Status:
Requested → Approved

---
## Testing Results

### Test Scenario

New onboarding request submitted.

### Expected Result

Flow executes automatically.

### Actual Result

Flow execution completed successfully.

Status updated to Approved.

### Outcome

PASS

---

## Key Concepts Demonstrated

* App Engine Studio
* Table Design
* Form Configuration
* Flow Designer
* Workflow Automation
* Security Roles
* ServiceNow Development Lifecycle

---

## Future Enhancements

* Email Notifications
* Approval Routing
* Dashboard Reporting
* Service Catalog Integration
* Asset Allocation Workflow

## Testing Results

### Test Scenario

New onboarding request submitted.

### Expected Result

Flow executes automatically.

### Actual Result

Flow execution completed successfully.

Status updated to Approved.

### Outcome

PASS

---

## Key Concepts Demonstrated

* App Engine Studio
* Table Design
* Form Configuration
* Flow Designer
* Workflow Automation
* Security Roles
* ServiceNow Development Lifecycle

---

## Future Enhancements

* Email Notifications
* Approval Routing
* Dashboard Reporting
* Service Catalog Integration
* Asset Allocation Workflow

