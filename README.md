# Inventory Management System

[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Tech Stack](https://img.shields.io/badge/Tech-HTML%2CCSS%2CJS%2CPHP%2CMySQL-blue)](#tentative-tech-stack)

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Purpose and University Applications](#purpose-and-university-applications)
- [Tentative Tech Stack](#tentative-tech-stack)
- [How It Works](#how-it-works)
- [Folder Structure](#folder-structure)
- [Future Improvements](#future-improvements)

---

## Overview
The **Inventory Management System** is a web-based application designed to help small businesses, organizations, or departments efficiently track and manage their inventory, recipes, and production.  

In a university context, it can be applied to manage materials in student-run cafes, labs, or departmental resources. The system automates inventory tracking, reduces manual errors, and provides clear visibility of stock. Production activities (like baking or assembling items) are linked to inventory usage, ensuring records are always accurate.

---

## Key Features
1. **Inventory Tracking**
   - Add, update, or remove inventory items.
   - Monitor stock levels automatically.
   - Keep records to prevent shortages.

2. **Recipe / Resource Management**
   - Store recipes or project instructions with materials.
   - Link ingredients/resources to inventory so usage automatically reduces stock.
   - Update recipes without affecting previous records.

3. **Production Logging**
   - Log production events (e.g., baked goods, assembled items).
   - Automatically deduct used inventory.
   - Maintain accurate records for reporting and planning.

4. **User Roles**
   - **Admin:** Full access to inventory, recipes/resources, production logs, and user management.
   - **Staff/Students:** Can log production or view inventory levels.

5. **Data Management & Reporting**
   - Centralized database for users, inventory, recipes, and production logs.
   - Easy to generate reports for tracking trends or planning purchases.

---

## Purpose and University Applications
This system helps:
- Reduce manual errors when tracking inventory or resources.
- Streamline production and resource usage.
- Enable university departments or student organizations to make informed decisions about purchasing and allocation.
- Save time for staff managing labs, materials, or student-run services.
- Promote accountability through user activity logs.

**Example scenarios in a university:**
- Student-run bakery or food service tracking ingredients and baked products.
- Laboratory or project materials monitored to avoid shortages.
- School stores keeping clear records for efficient restocking.

---

## Tentative Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Version Control:** Git / GitHub  

---

## How It Works
1. Users log in according to their role (admin or staff/student).  
2. Inventory items are added, updated, or removed.  
3. Recipes or project instructions are linked to inventory so that material usage is automatically deducted during production or activity logs.  
4. Production or usage logs maintain a full history, keeping inventory accurate and transparent.

---

## Folder Structure:
bakery_inventory_system/
├─ assets/ # Images, CSS, JS files
├─ config/ # Database connection and configuration files
├─ public/ # Publicly accessible files, like index.php
├─ src/ # PHP backend logic (controllers, models)
├─ database/ # Database schema or seed scripts
├─ README.md # Project documentation
└─ .gitignore # Files/folders Git should ignore



---

## Future Improvements
- Notification alerts for low-stock items or expired materials.
- Reporting dashboards to visualize inventory trends.
- Multi-user collaboration support for large departments.

---

*This system is designed to make inventory and production management easier, faster, and more accurate — whether in small businesses or university contexts.*