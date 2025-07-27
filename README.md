# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository!  
This project showcases a full-fledged data warehousing and analytics solution — from constructing the data warehouse to deriving actionable insights.  

Designed as a **portfolio project**, it reflects industry best practices in:
- Data Engineering
- Data Warehousing
- Analytics

Explore, learn, and dive into how raw data transforms into strategic decisions!

# 📊 Project Requirements

## 🏗️ Building the Data Warehouse (Data Engineering)

**🎯 Objective:**  
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**📋 Specifications:**
- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation on the data model to support both business stakeholders and analytics teams.

---

## 📈 BI: Analytics & Reporting (Data Analytics)

**🎯 Objective:**  
Develop SQL-based analytics to deliver detailed insights into:
- 🧠 **Customer Behavior**
- 📦 **Product Performance**
- 📊 **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](C:\Users\hp\Downloads\Data Architecture.drawio.png)


1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.
# License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share it with proper credit.

# About Me

Hi! I'm **Fathima**.  
I'm an Btech Cse Student and passionate about data field, I love turning raw data into meaningful insights.
