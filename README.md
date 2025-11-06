# Interport Cargo Enterprise Management System  
*Enterprise Solution Design & Agile Prototype Development*  
*Laravel 9.19 • MySQL • Node.js • ASP.NET Core Razor • Azure DevOps • Figma*

---

## Overview

This repository documents the **design and agile prototype development** of a new **Enterprise Management System (EMS)** for **Interport Cargo Services**, a leading Australian freight forwarding and customs brokerage organization.  

The system modernizes critical customer and logistics workflows by integrating **Quotation Management**, **Job Booking**, and **Outturn Processing** into a single digital platform.  
The project was delivered using an **Agile SCRUM framework** over multiple sprints, progressing from concept design to a fully functional prototype.

---

## Phase 1 – Enterprise Solution Design (Assessment Task 1)

### Objectives
- Conduct requirement analysis and system design for Interport Cargo’s digital transformation initiative.  
- Develop **business capability maps**, **user stories**, **acceptance criteria**, and **solution architecture**.  
- Deliver UML models, medium-fidelity wireframes, and a client presentation demonstrating system feasibility.

### Key Deliverables
| Category | Deliverable |
|-----------|-------------|
| **Business Analysis** | Capability mapping (L1 & L2), process decomposition, requirement prioritization |
| **Requirements Engineering** | User roles, epics, features, user stories, acceptance criteria |
| **Architecture Design** | Layered solution architecture (presentation, application, data, integration layers) |
| **System Modelling** | UML class, activity, and sequence diagrams |
| **UI/UX** | Medium-fidelity wireframes and style guide (Figma) |
| **Client Demonstration** | 20-minute presentation and design documentation bundle |

### Technology Stack
- **Backend Framework:** Laravel 9.19 (PHP MVC)  
- **Database:** MySQL 8  
- **Frontend:** Blade Templates + Node.js Toolchain  
- **Project Management:** Azure Boards (Azure DevOps)  
- **Design Tools:** Figma • Draw.io • Visual Paradigm  
- **Version Control:** Git / GitHub  

---

## Phase 2 – Agile Development Sprint 1 (Assessment Task 2)

### Sprint Context
Following approval of the design proposal, Interport Cargo commissioned a working prototype of the **Quotation Module**.  
The sprint ran from **15 September – 25 October 2025** (≈ 5 weeks) under the **SCRUM framework**, with weekly scrum meetings, sprint backlog tracking, and progressive delivery.  
The deliverable: a **functional prototype** demonstrating quotation workflows from registration to quotation issuance.

---

### Sprint Scope — User Stories

#### **Team User Stories (T1–T5)**
| ID | Role | Goal |
|----|------|------|
| **T1** | User (Customer / Employee) | Access the main dashboard for registration, login, and quotation requests. |
| **T2** | New Customer | Register details (first name, family name, email, phone, company, address, password). Passwords are hashed; email is the username. |
| **T3** | New Employee | Register details including role (Admin, Quotation Officer, Booking Officer, Warehouse Officer, Manager, CIO). |
| **T4** | User | Log out securely from the system. |
| **T5** | Quotation Officer | View all quotations with quotation number, client name, date issued, and status (Accept/Reject/Pending). |

#### **Individual User Stories (I1–I6) – Quotation Module (3.1.1)**  
| ID | Role | Description |
|----|------|-------------|
| **I1** | Existing Customer | Log in using validated credentials and access “Request Quotation.” |
| **I2** | Customer | Submit quotation request with request ID, source, destination, container count, package type, and job nature (import/export, packing, quarantine). |
| **I3** | Quotation Officer | Review quotation requests and accept/reject; notify customers of decision. |
| **I4** | Quotation Officer | Access Rate Schedule and generate quotation with charges and container details. |
| **I5** | Quotation Officer | Apply discount alerts based on job nature (per Appendix criteria) and submit final quotation. |
| **I6** | Customer | View received quotation and respond (accept/reject); notify officer of status update. |

---

### Sprint Deliverables

#### **Task 1 – Agile Development**
- Conducted weekly **SCRUM meetings** (one-page reports each week) covering progress, issues, and next steps.  
- Followed Agile iterations through Azure Boards for backlog management and sprint review.

#### **Task 2 – Prototype Development**

**2.1 User Interface Development**
- Developed ASP.NET Core Razor pages for core functions (registration, login, quotation workflow).  
- Implemented consistent navigation and layout aligned with UI/UX principles.  

**2.2 Functional Development**
- C# controllers and Entity Framework Core data flows using SQL Server / SQLite.  
- Modular logic per user story to support login, request submission, quotation processing, and notifications.  

**2.3 Code Quality**
- Refactored code per C# best practices and naming conventions.  
- Added XML documentation comments for public classes, methods, and key functions.  

**2.4 Testing**
- Performed black-box unit tests for selected user stories.  
- Verified data validation logic and quotation workflow consistency.

---

### Sprint Timeline

| Week | Focus | Output |
|------|--------|---------|
| **Week 9** | Sprint Planning & Setup | Backlog refinement, story assignment, Azure Boards setup |
| **Weeks 10–13** | Prototype Development (+ Mid-Break Extension) | Progressive UI and functionality builds |
| **Week 14** | Finalization & Testing | Integration testing and demo preparation |

---

### Project Management
- **Framework:** SCRUM (Weekly sprint reviews and retrospectives)  
- **Tools:** Azure Boards for sprint tracking and task ownership  
- **Meetings:** Weekly team SCRUM reports documented and reviewed by product owner  

---

## Repository Structure


---

## Tools & Technologies

| Category | Technology |
|-----------|-------------|
| **Frontend** | ASP.NET Core Razor • HTML • CSS • Bootstrap |
| **Backend** | C# .NET Core • Entity Framework Core |
| **Database** | SQL Server / SQLite |
| **Architecture Design** | Draw.io • Visual Paradigm |
| **UX Design** | Figma |
| **Project Management** | Azure DevOps Boards |
| **Version Control** | Git / GitHub |
| **Testing** | xUnit / MSTest for unit tests |

---

## Learning Outcomes Applied

- **ULO 3** – Justify recommended models and how they address organizational needs.  
- **ULO 4** – Configure fit-for-purpose enterprise systems.  
- **ULO 5** – Provide justified recommendations for future extensions.  
- **ULO 6** – Communicate professionally in written and visual formats to stakeholders.  

---

## License

© 2025 Interport Cargo Enterprise System Design Project.  
All materials are for **educational and portfolio demonstration purposes only**.

---

## Contact

**Ray Jui-Sheng (Ray) Chiang**  
[chiangjuisheng@gmail.com]  
[https://github.com/raychiang](https://github.com/raychiang)  
[LinkedIn](https://www.linkedin.com/in/ray-chiang-9b3449305/)

---

> *A professional enterprise-grade system prototype demonstrating agile delivery, enterprise architecture, and full-stack development practices within a real logistics context.*
