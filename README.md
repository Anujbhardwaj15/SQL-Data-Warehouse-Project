# 📊 SQL Data Warehouse Project

## **Medallion Architecture | Data Warehouse | ETL Processes | Data Modeling | Analytics | SQL Server**

Welcome to the **SQL Data Warehouse and Analytics Project** Repository!

This project showcases a comprehensive data warehousing and analytics solution. It covers everything from building a modern data warehouse to deriving actionable business insights. Designed as a portfolio project, it demonstrates industry best practices in data engineering and analytics.

---

## 🚀 **Project Overview**

- **Objective:** Develop a modern data warehouse using **SQL Server** to consolidate sales data, enabling analytical reporting and informed decision-making.
- **Architecture:** Based on the **Medallion Architecture** (Bronze, Silver, Gold layers).
- **Focus Areas:** Data Engineering, ETL Processes, Data Modeling, and Business Intelligence (BI).

---

## 📋 **Project Requirements**

### **1. Data Sources**

- **CRM Data:**
  - `cust_info.csv`
  - `prd_info.csv`
  - `sales_details.csv`

- **ERP Data:**
  - `CUST_AZ12.csv`
  - `LOC_A101.csv`
  - `PX_CAT_G1V2.csv`

### **2. Specifications**

- **Data Quality:** Cleanse and resolve data quality issues before analysis.
- **Integration:** Combine CRM and ERP data into a unified data model for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Clear documentation to support business stakeholders and analytics teams.

---

## 📊 **Business Intelligence & Analytics**

### **Objective:**  
Develop **SQL-based analytics** to deliver insights into:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights help stakeholders make data-driven decisions and improve business performance.

---

## ⚙️ **Database Setup & ETL Process**

### **Database Structure:**
- **Bronze Layer:** Raw data storage.
- **Silver Layer:** Cleaned and transformed data.
- **Gold Layer:** Aggregated data for reporting and analysis.

### **ETL Process:**
- **Extract:** Load data from CSV files.
- **Transform:** Cleanse and format data using SQL.
- **Load:** Insert data into the appropriate database tables.
- **Error Handling:** Robust error management to ensure data integrity.

---

## 🗂️ **SQL Scripts & Procedures**

- **Database Creation:** Sets up the `DataWarehouse` database.
- **Schema Creation:** Bronze, Silver, and Gold layers for different data stages.
- **Table Creation:** Defines tables for CRM and ERP data.
- **ETL Stored Procedure:** Automates data loading from CSV files into the warehouse.

---

## 📈 **How to Run the Project**

### ✅ **Prerequisites:**
- **SQL Server** installed.
- **CSV Files** available in the directories.

