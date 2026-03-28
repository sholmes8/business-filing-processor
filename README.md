# Business Filing Workflow System Analysis  
*(Cogency-Inspired Systems Analysis Project)*

> System design and workflow optimization project applying SDLC principles to real-world business processes

> ⚠️ **Note:** This repository is private due to the use of internal workflow concepts. All documentation has been generalized to protect company confidentiality. Detailed explanations can be provided upon request.

---

## 📌 Project Overview

This project analyzes a compliance-driven business filing workflow inspired by real-world entity filing operations. The goal of the project is to evaluate an existing manual process, identify inefficiencies, and design a modernized system solution that improves data accuracy, operational efficiency, and tracking visibility.

The project demonstrates core **Information Systems and Business Analyst skills**, including:
- Systems analysis  
- Workflow documentation  
- Process improvement  
- Requirements gathering  
- Data validation  
- Technical documentation  

---

## 🎯 Project Objectives

- Analyze an existing filing workflow used in compliance-based operations  
- Identify inefficiencies, error points, and process gaps  
- Design an improved “To-Be” system model  
- Define functional and non-functional system requirements  
- Propose a scalable solution for tracking, validation, and reporting  
- Demonstrate analytical and documentation skills applicable to analyst roles  

---

## 🧩 Problem Statement

The current filing workflow relies heavily on manual review, fragmented tracking, and inconsistent validation practices. This results in:

- High rejection and resubmission rates  
- Limited visibility into filing status  
- Manual data entry errors  
- Inconsistent documentation handling  
- Lack of standardized reporting  

A centralized system is needed to improve efficiency, accuracy, and auditability.

---

## 🛠 Tools & Technologies

- SQL (data analysis & reporting concepts)
- Python (data validation logic)
- Draw.io (workflow diagrams)
- Microsoft Excel (user stories & backlog)
- GitHub (version control & documentation)

---

## 📂 Project Deliverables

- **System Requirements Document (SRD)**
- **As-Is Workflow Diagram**
- **To-Be Workflow Diagram**
- **User Stories & Backlog**
- **Process Improvement Recommendations**
- **Key Performance Metrics (KPIs)**

---

## 🔄 Workflow Overview

### As-Is Process
- Manual intake of filing requests  
- Manual document review and validation  
- Status tracking through spreadsheets or email  
- Rejections handled reactively  
- Limited reporting or trend analysis  

### To-Be Process
- Centralized intake system  
- Automated validation rules  
- Document version control  
- Status tracking with audit history  
- Rejection categorization and reporting  
- Operational dashboards for monitoring performance  

---

## 📋 System Features

### Functional Requirements
- Filing intake and data capture  
- Document upload and versioning  
- Validation of required fields  
- Status tracking and audit logs  
- Rejection reason categorization  
- Reporting and performance metrics  

### Non-Functional Requirements
- Secure access control  
- Data integrity and traceability  
- High usability and consistency  
- Scalable design for future enhancements  

---

## 📊 Key Metrics Tracked

- Filing turnaround time  
- Rejection rate  
- First-pass approval rate  
- Volume of filings per processor  
- Common rejection reasons  

---

## 🧠 Skills Demonstrated

- Systems Analysis & Documentation  
- Business Process Modeling  
- Requirements Gathering  
- Workflow Optimization  
- Data Validation  
- Technical Writing  
- Analytical Thinking  

---

## 📁 Repository Structure

---

## 💻 Technical & Engineering Perspective

While this project focuses on systems analysis and workflow optimization, it is designed with software development implementation in mind.

The proposed system can be translated into a full-stack application with:

- Backend services for workflow processing and validation (Node.js / Python)
- Database design for entity filings, status tracking, and audit logs (SQL)
- Frontend interface for intake, tracking, and reporting (React)
- API-driven architecture for scalability and integration

This demonstrates the ability to bridge **business requirements and technical implementation**, aligning with real-world software development and SDLC practices.

## 🔧 API Design (Mock Implementation)

The proposed system can be implemented using a RESTful API to manage filing workflows, validation, and tracking.

### Example Endpoints

**Create Filing**
POST /api/filings
- Creates a new filing request

**Get Filing Status**
GET /api/filings/{id}
- Retrieves current status and details of a filing

**Update Filing Status**
PUT /api/filings/{id}/status
- Updates filing status (Pending, Submitted, Rejected, Approved)

**Validate Filing**
POST /api/filings/{id}/validate
- Runs validation checks on filing data

**Get Reports**
GET /api/reports
- Returns filing metrics and performance data

This API structure demonstrates how the workflow system can be translated into a scalable backend service.

## 🗄️ Database Schema (Conceptual)

The system is designed using a relational database structure:

### Tables

**Filings**
- filing_id (Primary Key)
- entity_name
- filing_type
- status
- submission_date

**Documents**
- document_id (Primary Key)
- filing_id (Foreign Key)
- file_name
- version
- uploaded_at

**Users**
- user_id (Primary Key)
- name
- role

**Rejections**
- rejection_id (Primary Key)
- filing_id (Foreign Key)
- reason
- timestamp

This schema supports structured data storage, audit tracking, and reporting capabilities.

## 🏗️ System Architecture

The proposed system follows a layered architecture:

**Frontend**
- User interface for filing intake and tracking (React)

**Backend**
- API layer handling business logic and validation (Node.js / Python)

**Database**
- Relational database storing filings, documents, and status data (SQL)

**Workflow Engine**
- Handles validation rules, status transitions, and audit logging

**Reporting Layer**
- Generates dashboards and operational insights

This architecture supports scalability, modularity, and real-time workflow tracking.
