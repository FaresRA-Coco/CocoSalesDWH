# CocoSalesDWH
A practical roadmap for creating a modern data warehouse in SQL Server, integrating ETL processes, robust data models, and advanced analytics.


## 🔔 Notice  

This project is a **learning and portfolio adaptation**.  
For the **original full project**, please visit 👉  
🌐 [DataWithBaraa/sql-data-warehouse-project](https://github.com/DataWithBaraa/sql-data-warehouse-project/tree/main)  

All credit goes to **DataWithBaraa** 🙌  
This repository is meant for **practice, study, and demonstration purposes** only. 🚀


# 🏛️ Data Warehouse & Analytics Project

Welcome to the **Data Warehouse & Analytics Project repository** 🚀  
This portfolio project showcases a complete data warehousing and analytics solution — from raw data ingestion to actionable insights. It highlights **industry best practices** in data engineering, ETL, modeling, and reporting.

---

## 📐 Data Architecture (Medallion Layers)

- **Bronze Layer**: Raw data ingested directly from ERP and CRM CSV files into SQL Server.  
- **Silver Layer**: Cleansed, standardized, and normalized datasets prepared for analysis.  
- **Gold Layer**: Business-ready data modeled into a star schema, optimized for reporting and dashboards.  

---

## 📖 Project Scope

This project demonstrates:

- **Data Architecture**: Designing a modern warehouse using the Bronze–Silver–Gold Medallion approach.  
- **ETL Pipelines**: Extracting, transforming, and loading ERP/CRM data into SQL Server.  
- **Data Modeling**: Building fact and dimension tables for analytical queries.  
- **Analytics & Reporting**: Delivering SQL-based dashboards and insights.  

---

## 🎯 Skills & Roles Highlighted

This repository is ideal for professionals and students aiming to showcase expertise in:

- SQL Development  
- Data Architecture & Engineering  
- ETL Pipeline Design  
- Data Modeling  
- Business Intelligence & Analytics  

---

## 🛠️ Tools & Resources

All resources are **free to use**:

- **Datasets**: ERP & CRM CSV files  
- **SQL Server Express**: Lightweight database engine  
- **SSMS**: SQL Server Management Studio for database management  
- **GitHub**: Version control & collaboration  
- **DrawIO**: Architecture diagrams & data flows  
- **Notion**: Project templates & task tracking  

---

## 🖊️ Project Requirements

### Objective (Data Engineering)
- Build a modern SQL Server warehouse consolidating ERP & CRM sales data.  
- Cleanse and integrate datasets into a unified analytical model.  
- Focus on the latest dataset (no historization).  
- Provide clear documentation for business and analytics teams.  

### Objective (Data Analysis)
- Develop SQL-based analytics to deliver insights into:  
  - Customer behavior  
  - Product performance  
  - Sales trends  

These insights empower stakeholders with **strategic decision-making tools**.  

---

## 📂 Repository Structure

```plaintext
data-warehouse-project/
├── datasets/            # ERP & CRM raw CSVs
├── docs/                # Documentation & diagrams
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── naming-conventions.md
├── scripts/             # SQL ETL scripts
│   ├── bronze/
│   ├── silver/
│   ├── gold/
├── tests/               # Quality checks
├── README.md            # Overview & instructions
├── LICENSE              # License info
├── .gitignore           # Git ignore rules
└── requirements.txt     # Dependencies
