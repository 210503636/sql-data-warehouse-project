# SQL Data Warehouse Project

**Building a Modern Data Warehouse with SQL Server — ETL Pipelines, Data Modeling, and Analytics**

This portfolio project showcases the end-to-end development of a modern data warehousing and analytics solution. It highlights industry best practices in data engineering and analytics, from ingesting raw data to delivering business-ready insights.

---

## 🏗️ Architecture Overview

The project adopts the **Medallion Architecture** approach, implementing three distinct layers:

![data_architectureTG](https://github.com/user-attachments/assets/06ff45cc-1af3-4403-acf2-7c566b60df96)

- **🔹 Bronze Layer**  
  Stores raw data ingested *as-is* from source systems. Data is extracted from CSV files and loaded into SQL Server.

- **🔸 Silver Layer**  
  Performs data cleansing, standardization, and normalization to ensure data quality and consistency.

- **🟡 Gold Layer**  
  Contains curated, business-ready data modeled into a **star schema** for optimized reporting and analytics.

---

## 📦 Project Components

### 1. **Data Architecture**
- Design and implementation of a modern SQL Server data warehouse using the Medallion layered approach.

### 2. **ETL Pipelines**
- End-to-end ETL development:
  - **Extract** data from ERP and CRM source systems (CSV format)
  - **Transform** to address data quality issues
  - **Load** into structured data models

### 3. **Data Modeling**
- Design of **fact** and **dimension** tables  
- Star schema implementation to support analytical queries and BI tools

### 4. **Analytics & Reporting**
- Development of SQL-based queries to extract actionable insights  
- Focus areas include:
  - **Customer Behavior**
  - **Product Performance**
  - **Sales Trends**

---

## 🎯 Project Goals

### 📊 Data Engineering: Build the Data Warehouse

- **Objective**: Consolidate sales and customer data from multiple sources to enable analytical reporting and informed decision-making.

- **Specifications**:
  - **Data Sources**: ERP and CRM (CSV files)
  - **Data Cleansing**: Address and resolve data quality issues
  - **Integration**: Merge sources into a unified, analytics-ready model
  - **Scope**: Focused on current datasets (no historization)
  - **Documentation**: Clear schema descriptions for business and technical users

### 📈 Data Analysis: Enable Business Intelligence

- **Objective**: Deliver high-impact analytics using SQL to inform strategy and operations

- **Key Insights**:
  - Customer segmentation and lifetime value
  - Product-level sales performance
  - Market and seasonal sales trends

---

## 📝 Deliverables

- ETL Scripts  
- SQL Data Models (DDL)  
- SQL-based Analytical Queries  
- Data Model Documentation  
- Architecture Diagram
