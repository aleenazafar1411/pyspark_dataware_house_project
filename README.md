# 🏢 Pyspark Data Warehouse & Analytics Portfolio Project

Welcome to my **PySpark Data Warehouse & Analytics Project**! 🚀  
This project showcases a complete **end-to-end data engineering workflow**, starting from raw data ingestion to business-ready analytics.

It is specially designed as a **portfolio project** to demonstrate real-world practices in:
- Data Engineering  
- ETL Development with PySpark  
- Data Modeling  
- Data Analytics using PySpark  

---

## 🖼️ High-Level Architecture

This architecture follows the **Medallion Design Pattern** with three main layers:
- Bronze (Raw Data)  
- Silver (Cleaned & Standardized Data)  
- Gold (Business-Ready Data)  

---

## 🏗️ Data Architecture Overview

### 🟤 Bronze Layer – Raw Zone
- Stores raw data exactly as received  
- Data is loaded from **CSV files** using PySpark's `spark.read` API  
- No transformations applied  
- Used for audit & backup purposes  

### ⚪ Silver Layer – Clean Zone
- Data cleaning & validation using PySpark DataFrame operations  
- Data type corrections & casting  
- Duplicate handling  
- Standardization & normalization  

### 🟡 Gold Layer – Business Layer
- Final reporting-ready data  
- Fact & Dimension tables/views  
- Star schema modeling  
- Used directly for analytics & BI via Spark SQL or BI tools connected to Hive Metastore  

---

## 📖 Project Summary

This project covers the following key areas:

- Modern Data Warehouse Design using Medallion Architecture  
- Complete ETL pipelines implemented in PySpark DataFrame API  
- Dimensional Data Modeling (Fact & Dimensions)  
- Business-level Analytics using PySpark transformations and Spark SQL  
- Fully documented structure for learning & reuse  

---

## 🎯 Skills Demonstrated

This repository highlights strong hands-on experience in:

- PySpark Development  
- Data Warehousing  
- ETL Pipeline Development with Spark  
- Data Cleaning & Transformation using PySpark functions  
- Star Schema Modeling  
- Business Analytics  

---

## 🛠️ Tools & Technologies Used

- Apache Spark (PySpark)  
- Hive Metastore (for table/view management)  
- CSV Data Sources  
- Draw.io (for diagrams)  
- Git & GitHub  

---

## 🚀 Project Objectives

- Build a centralized data warehouse for sales analytics  
- Integrate data from **CRM & ERP systems** using PySpark  
- Ensure high data quality through Spark DataFrame transformations  
- Enable analytical reporting via Spark SQL and BI tools  
- Support business decision-making with scalable data pipelines  

---

## 📊 Analytics Scope

The Gold Layer supports analysis on:

- Customer Behavior  
- Product Performance  
- Sales Trends  
- Revenue Insights  

These insights help stakeholders take **data-driven decisions**.

---
## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
```
---
## ✅ Project Requirements Covered

### 🔧 Data Engineering
- Source Integration (ERP & CRM) using PySpark  
- Data Cleansing & Validation with Spark DataFrame API  
- Data Modeling & Star Schema Design  
- ETL Automation with PySpark  
- Proper Documentation  

### 📈 Data Analytics
- Reporting and analysis using Spark SQL and PySpark  
- KPI generation using Spark transformations  
- Business insights  

---

## 👩‍💻 Author

**Aleena Zafar**  
Data Engineering Intern | PySpark Developer  

---

## 🛡️ License

This project is created for learning and portfolio demonstration purposes.
