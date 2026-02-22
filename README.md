# Database Systems

This repository contains the complete series of projects developed for the **Database Systems** course.

## 📂 Project Structure

```text
C:.
│   README.md
│   
├───Project #1
│       PRJ1.sql                    # DDL, DML, and Analytical Views
│       Project 1 - Databases.pdf
│       
├───Project #2
│       DDLPRJ2.ddl                 # Data Definition Language
│       DMDPRJ2.dmd                 # Data Model Design file
│       PRJ2.sql                    # Relational implementation & Queries
│       Project 2 - Databases.pdf
│
└───Project #3
        DDLPRJ3.sql                 # Database Schema & Constraints
        PRJ3.sql                    # Procedural Logic & Triggers
        Project 3 - Databases.pdf
        Tests.sql                   # Validation scripts for automation

```

---

## 🚀 Project Summaries

### 1. Analytical Insurance Systems (Project #1)

**Focus:** Relational Foundations & Data Analysis.

* **Goal:** Design a robust system for insurance policy management.
* **Key Implementation:** Developed complex SQL views to calculate dynamic premiums. By joining policy data with regional risk factors and coverage types, the system automates financial reporting.
* **Highlight:** Use of Common Table Expressions (CTEs) to generate multi-dimensional demographic reports (gender vs. location distributions).

### 2. Clinical Records & Claims Hierarchy (Project #2)

**Focus:** Advanced ER Modeling & Relationship Logic.

* **Goal:** Model a healthcare environment including medical staff, appointments, and insurance disputes.
* **Key Implementation:** Designed a **recursive relationship model** for insurance claims. This allows the system to track how a "Denied Claim" evolves into a "Dispute Process" through various legal stages.
* **Highlight:** Handling of multi-valued attributes (medical degrees, patient allergies) and inheritance in claim types.

### 3. "Gama" Logistics & Active Automation (Project #3)

**Focus:** PL/SQL, Triggers, and Corporate Auditing.

* **Goal:** Create an "Active" database for a global commercial supplier.
* **Key Implementation:** - **Automated Credit Control:** PL/SQL triggers that monitor payments in real-time, blocking transactions and generating notifications if a client exceeds their credit limit.
* **Audit Logs:** Implementation of `LOG` tables that automatically record the history of updates and deletions (`OLD` vs `NEW` values) for security and compliance.


* **Highlight:** Transitioning from passive data storage to an automated business rule engine.

---

## 🛠️ Technical Stack

* **Database Engines:** Oracle SQL, PL/SQL, PostgreSQL.
* **Modeling Tools:** ER-Studio, SQL Data Modeler, Oracle SQL Developer.
* **Techniques:** ACID Compliance, 3rd Normal Form (3NF), Trigger-based Automation, Role-Based Access Control (RBAC).

---

## 👥 Development Team

* Daniel Castro
* Laura Garzón
* Juan Rozo
* Maria P. Rodríguez

**Institution:** Pontificia Universidad Javeriana

**Instructor:** Julio Omar Palacio Niño