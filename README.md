# 📦 Inventory Optimization Using Advanced SQL Analytics

A comprehensive SQL-powered framework to streamline inventory operations, uncover inefficiencies, and deliver actionable insights across a distributed retail network. This project leverages relational modeling, analytical SQL, and data visualization to enable smarter inventory decisions.

---

## 🌐 Live Interactive Dashboard

Monitor inventory health, KPIs, and trends in real-time via our hosted dashboard:

🔗 https://retail-data-dashboard.vercel.app/

---

## 🔍 Project Overview

This solution brings together data engineering and business analytics through a structured SQL backend. Key components include:

- **Relational Data Model:** Core tables for `products`, `stores`, `inventory movements`, and `KPI metrics` — fully normalized with appropriate constraints and indexing.
- **Data Transformation & Aggregation:** SQL scripts ingest raw CSV files, clean and structure the data, and produce ready-to-use views for insights.
- **Insights Engine:** Views and queries capture real-time operational indicators such as inventory turnover, product classification, reorder status, and demand seasonality.
- **Reporting Layer:** Executive-level dashboards and summaries tailored for business users and store managers.

---

## 📈 Business Value Delivered

Through robust SQL analytics, the project supports:

- 📌 Identifying stock shortages and reorder needs
- 📊 Tracking high and low-performing products across categories
- 🧮 Classifying products using ABC methodology for inventory prioritization
- 📆 Forecasting seasonal demand patterns
- 🛑 Detecting high-risk areas prone to stockouts

---

## 📂 Repository Contents

- `sql-scripts/` — Modular SQL files for schema creation, transformations, and analytical queries  
- `csv-output/` — Query result exports used for reporting and dashboard integration  
- `ERD-mysql-workbench/` — MySQL Workbench files (`.mwb`, `.bak`) for schema design  
- `documentation/` — Includes ER diagrams, executive insights, and query-level documentation  
- `web-preview/index.html` — Demo HTML file for quick dashboard rendering (static)

---

## 📄 Key Resources

- **SQL Schema Documentation** – Breakdown of all tables, keys, and indexes  
- **Analytical View Definitions** – Descriptions of reusable views like `vw_inventory_turnover`, `vw_reorder_analysis`  
- **Executive Summary Report** – High-level overview with visual insights and recommendations  
- **ER Diagram (PDF)** – Visual map of schema structure for quick reference

---

## 🧰 Tech Stack

- **Database:** MySQL 8.0+  
- **Query Language:** Advanced SQL (Views, Joins, Aggregations)  
- **Data:** CSV-imported transactional and master data  
- **Frontend (External):** HTML + Vanilla JS (for visualization)

---

## 🤝 Contributions & Acknowledgments

Built as part of a data analytics initiative aimed at bridging SQL and business intelligence. Contributions, issues, and feature requests are welcome — feel free to fork the repo or open a discussion.
