# 🛒 E-Commerce Sales Pipeline Analysis
> **Strategic Data Engineering & Executive BI Analytics**

[![SQL Server](https://img.shields.io/badge/SQL_Server-Enterprise_Warehouse-red?style=for-the-badge&logo=microsoft-sql-server)](https://github.com/Business-Analyst-Pankaj-Joshi/Ecommerce-Sales-Data-Pipeline)
[![Power BI](https://img.shields.io/badge/Power_BI-Advanced_Modeling-yellow?style=for-the-badge&logo=powerbi)](https://github.com/Business-Analyst-Pankaj-Joshi/Ecommerce-Sales-Data-Pipeline)
[![DAX](https://img.shields.io/badge/DAX-Time_Intelligence-blue?style=for-the-badge)](https://github.com/Business-Analyst-Pankaj-Joshi/Ecommerce-Sales-Data-Pipeline)

---

## 🌟 Project Overview
This project transforms raw, fragmented e-commerce data into a **High-Impact Executive Dashboard**. Moving beyond basic reporting, I engineered a full lifecycle pipeline: **Excel Audit** ➔ **SQL Server Warehousing** ➔ **Power BI Star-Schema Modeling**.



---

## 🏗️ The Technical Stack
* **Data Ingestion:** Raw E-Commerce Sales (Excel)
* **Database Management:** SQL Server (SSMS) - Engineered for referential integrity.
* **Architecture:** Power BI **Star Schema** (Optimized for performance).
* **Intelligence:** Advanced DAX (YoY Growth, PYTD, & Momentum measures).

---

## 🚀 The Data Journey

### 1. Data Engineering (SQL Server)
Instead of direct import, I migrated the dataset into **SSMS** to simulate a real-world enterprise environment.
* **Warehouse Design:** Created `E-Commerce_Database`.
* **Integrity:** Optimized data types to reduce storage footprint.
* **Impact:** Established a single source of truth for the BI layer.

![SQL Setup](./Screenshort/Screenshot%202025-12-18%20110904.png)

### 2. Data Modeling (High-Performance Star Schema)
In Power BI, I designed a **Star Schema** to eliminate redundant joins and optimize query speed.
* **Fact Table:** `ecommerce_data`.
* **Dimension Tables:** `calender` (Date Table) and `us_state_long_lat` (Geospatial).
* **Relationship:** 1-to-many relationships for seamless cross-filtering.

![Data Model](./Screenshort/Screenshot%202025-12-18%20112134.png)

### 3. Advanced DAX & Business Logic
Metrics are logically separated into a `_All_Measures` table for clean documentation.
* **Key KPI Logic:** `PYTD Sales`, `YOY Profit Margin`, and `Dynamic KPI Color Coding`.
* **Intelligence:** Automated Year-over-Year comparisons to track business health.

![Measures Table](./Screenshort/Screenshot%202025-12-18%20115309.png)

---

## 📊 Final Interactive Dashboard
![Final Dashboard](./Screenshort/Screenshot%202025-12-16%20123141.png)

---

## 💡 Executive Insights Generated
* **Revenue Tracking:** Identified a YTD Sales total of **$11.53M** with specific focus on high-growth periods.
* **Regional Intelligence:** Visualized top-performing states to guide marketing spend.
* **Product Health:** Identified 'Bottom 5' products to optimize inventory and reduce overstocking costs.

---

## 📂 Project Assets
| File Type | Description | Link |
| :--- | :--- | :--- |
| **SQL Script** | Full Schema & Constraints | [📄 View Script](./Database_setup.zip) |
| **Power BI** | Interactive Dashboard (.pbix) | [📊 Download File](./e-commerce_dasboard.zip) |
| **Raw Data** | Audited Dataset | [📁 View Raw Data](./Raw_file/Raw_Sales_Data.xlsx) |

---

### 📫 Connect for Collaboration
[LinkedIn](https://www.linkedin.com/in/pankaj-joshi-6b7868391) | [Email](mailto:pankajmohanjoshi.official@gmail.com)
