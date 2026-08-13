# 📊 Data Warehouse and Analytics Project

A comprehensive **Data Warehouse and Analytics solution** built with **SQL Server**, demonstrating industry best practices in data engineering, data modeling, ETL, and analytics.

The project follows the **Medallion Architecture** with Bronze, Silver, and Gold layers and integrates data from ERP and CRM source systems into a business-ready **Star Schema**.

---

## 🏗️ Data Architecture

The project follows a **Medallion Architecture** consisting of three layers:
![Image description](img.png)

### 🥉 Bronze Layer

* Stores raw data as-is from source systems.
* Data is imported from CSV files into SQL Server.
* Minimal transformations are applied.

### 🥈 Silver Layer

* Cleans and standardizes raw data.
* Handles data quality issues.
* Performs transformations and normalization.
* Prepares data for analytical modeling.

### 🥇 Gold Layer

* Contains business-ready data.
* Implements a **Star Schema**.
* Provides optimized fact and dimension tables for reporting and analytics.

---

## 📖 Project Overview

This project covers the complete data warehousing lifecycle:

* 🏗️ **Data Architecture** — Designing a modern data warehouse using Bronze, Silver, and Gold layers.
* 🔄 **ETL Pipelines** — Extracting, transforming, and loading data from source systems.
* 🧩 **Data Modeling** — Developing fact and dimension tables optimized for analytical queries.
* 📊 **Analytics & Reporting** — Creating SQL-based reports to generate actionable business insights.
* 🧪 **Data Quality** — Identifying and resolving data quality issues before analysis.
* 📚 **Documentation** — Documenting the architecture, data models, datasets, and naming conventions.


## 🛠️ Tools & Technologies

| Tool                                    | Purpose                                               |
| --------------------------------------- | ----------------------------------------------------- |
| **SQL Server Express**                  | Database and data warehouse                           |
| **SQL Server Management Studio (SSMS)** | Database management and SQL development               |
| **Draw.io**                             | Architecture, data flow, ETL, and data model diagrams |
| **Git & GitHub**                        | Version control and project management                |
| **CSV**                                 | Source datasets                                       |

---
