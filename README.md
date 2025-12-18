
# 🛒 E-Commerce Sales Pipeline Analysis
**An End-to-End Data Engineering & Analytics Project**

## 🌟 Project Overview
This project demonstrates a professional data workflow—transforming raw, fragmented e-commerce data into a high-impact executive dashboard. I moved data through a full lifecycle: **Excel** for initial auditing, **SQL Server** for structured storage, and **Power BI** for advanced modeling and visualization.

---

## 🏗️ The Technical Stack
* **Data Source:** Raw E-Commerce Sales Data (Excel)
* **Database:** SQL Server (SSMS)
* **Modeling:** Power BI (Star Schema)
* **Analytics:** Advanced DAX (Time Intelligence & Dynamic Measures)

---

## 🚀 The Data Journey

### 1. Data Engineering (SQL Server)
I migrated the dataset into **SQL Server Management Studio (SSMS)**. 
* Developed the `E-Commerce_Database`.
* Optimized data types and ensured referential integrity.
* **Why?** This mimics real-world enterprise environments where data is pulled from a live server.

![SQL Setup](Screenshot/Screenshot%202025-12-18%20110904.png)

### 2. Data Modeling (Star Schema)
In Power BI, I designed a **Star Schema** to optimize query performance.
* **Fact Table:** `ecommerce_data`
* **Dimension Tables:** `calender` and `us_state_long_lat`.
* **Relationship:** Established 1-to-many relationships for seamless cross-filtering.

![Data Model](Screenshot/Screenshot%202025-12-18%20112134.png)

### 3. Advanced DAX Calculations
All measures are organized in a dedicated `_All_Measures` table. 
* **Metrics:** `PYTD Sales`, `YOY Profit Margin`, and `Dynamic Formatting` measures for KPIs.

![Measures Table](Screenshot/Screenshot%202025-12-18%20115309.png)

---

## 📊 Final Interactive Dashboard
![Final Dashboard](Screenshot/Screenshot%202025-12-16%20123141.jpg)


---

## 📂 Project Assets & Downloads
To view the technical work behind this dashboard, you can access the files below:

| File Type | Description | Link |
| :--- | :--- | :--- |
| **SQL Script** | Full Database Setup & Schema | [📄 View SQL Script](./Database_setup.zip) |
| **Power BI** | Interactive Dashboard (.pbix) | [📊 Download PBIX](./e-commerce_dasboard.zip) |
| **Raw Data** | Original Excel Dataset | [📁 View Raw Data](./Raw_file/Raw_Sales_Data.xlsx) |

---

## 💡 Business Impact
The final dashboard provides actionable insights:
* **Revenue Tracking:** Identified a YTD Sales total of **$11.53M**.
* **Regional Strategy:** Visualized high-performance states for targeted marketing.
* **Inventory Focus:** Identified Bottom 5 products to prevent overstocking.
