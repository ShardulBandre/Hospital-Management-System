# 🏥 Hospital Management System

A desktop application built in **Java** using **Swing** and **AWT** for GUI and **MySQL** for backend persistence. This system simplifies hospital reception workflows, handling patient admissions, bed/ward allocation, staff management, payment tracking, and discharge operations.

---

## 🚀 Features

- **Secure Authentication:** Login system with database credential verification and error handling.
- **Patient Admission:** Register new patients with identification details (e.g., Aadhaar/Govt ID), symptoms, deposit amount, and auto-generated timestamp.
- **Room & Bed Management:** 
  - Tracks status (Available / Occupied) across General Wards, Private Wards, and ICUs.
  - Room search and filter by category.
- **Patient Updates & Billing:**
  - Update patient records, room reassignments, and deposit/billing calculations.
  - Automatic calculation of pending balances against room rates.
- **Discharge System:** Quick discharge handling via patient ID with check-in/check-out timestamp logging and bed release.
- **Hospital Directory & Staff Info:** View employee, doctor, and nurse lists along with departmental reception contacts.
- **Ambulance Tracking:** View available ambulance units and driver contact details.

---

## 🛠️ Tech Stack & Tools

- **Programming Language:** Java (JDK 8+)
- **GUI Framework:** Java Swing & AWT
- **Database:** MySQL / MySQL Workbench
- **Database Connectivity:** JDBC (Java Database Connectivity)
- **Supported IDEs:** IntelliJ IDEA, Eclipse, NetBeans, or VS Code

---

## 🗄️ Database Setup

1. Open **MySQL Workbench** (or MySQL CLI).
2. Create a new database:
   ```sql
   CREATE DATABASE hospital_management_system;
   USE hospital_management_system;
