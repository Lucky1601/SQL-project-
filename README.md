# SQL Database Implementation & Analytics Projects

This repository contains SQL scripts for two distinct database schemas designed to handle banking operations and e-commerce order management. These projects demonstrate database design, CRUD operations, complex joins, and automation via triggers.

## 🚀 Projects Overview

### 1. Bank Management System (`Bank1`)
A relational database designed to manage customer accounts, branch locations, and employee data.
* **Key Features:** Primary/Foreign key constraints, data normalization, and transaction tracking.
* **Advanced Logic:** Includes an `AFTER INSERT` trigger on the `transaction` table to automatically update account balances based on deposits or withdrawals.
* **Analytic Queries:** Covers customer segmentation by occupation, balance sorting, and identifying high-value customers.

### 2. E-commerce Case Study (`casestudy`)
A robust schema for a retail platform managing customers, products, addresses, and order fulfillment.
* **Entities:** `ONLINE_CUSTOMER`, `PRODUCT`, `ORDER_HEADER`, `SHIPPER`, and `ADDRESS`.
* **Business Logic:**
    * Dynamic pricing updates using `CASE` statements based on product categories.
    * Inventory status tracking (Low stock/In stock/Enough stock) with category-specific thresholds.
    * Geographic and product-class filtering for targeted customer analysis.

## 🛠️ Tech Stack
* **Language:** SQL (MySQL/MariaDB compatible)
* **Tools:** Data Wrangling, Relational Database Design (RDBMS)

## 📖 How to Use
1.  Ensure you have a SQL environment installed (e.g., MySQL Workbench, DBeaver).
2.  Run the script to create the schemas and populate the tables with sample data.
3.  Execute the queries provided at the end of each section to see the data analysis in action.

---
*Developed as part of an MBA coursework portfolio focused on Business Analytics.*
