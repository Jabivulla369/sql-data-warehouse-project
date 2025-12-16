# sql-data-warehouse-project
# Data Warehouse and Analytics Project
Welcome to the **Data Warehouse and Analytics Project** 🚀
This repository showcases an end-to-end **data warehousing and analytics solution**, covering everything from data ingestion to business-ready insights. Built as a portfolio project, it demonstrates real-world, industry-standard practices in **data engineering, data modeling, and analytics**.

---

## 🏗️ Data Architecture

This project is designed using the **Medallion Architecture**, consisting of **Bronze**, **Silver**, and **Gold** layers to ensure scalable, reliable, and analytics-ready data.

![Data Architecture]<img width="1231" height="737" alt="Data Arch" src="https://github.com/user-attachments/assets/a2e38c5e-10da-498b-9be8-68957f710f8f" />


### Architecture Layers

1. **Bronze Layer (Raw Data)**

   * Stores source data in its original format.
   * Data is ingested directly from **CSV files** into a **SQL Server database**.
   * Serves as the immutable source of truth.

2. **Silver Layer (Cleaned & Transformed Data)**

   * Handles data cleansing, standardization, and normalization.
   * Resolves data quality issues and prepares datasets for analytics.

3. **Gold Layer (Business-Ready Data)**

   * Contains curated, analytics-ready datasets.
   * Data is modeled using a **star schema** optimized for reporting and performance.

---

## 📖 Project Overview

This project focuses on designing and implementing a modern data warehouse to support analytical use cases. Key components include:

1. **Data Architecture Design**

   * Implementation of Medallion Architecture (Bronze, Silver, Gold).

2. **ETL Pipelines**

   * End-to-end extraction, transformation, and loading of data from multiple source systems.

3. **Data Modeling**

   * Creation of fact and dimension tables optimized for analytical queries.

4. **Analytics & Reporting**

   * Development of SQL-based analytical queries and reports to generate actionable insights.

🎯 This repository is ideal for professionals and learners looking to demonstrate expertise in:

* SQL Development
* Data Architecture
* Data Engineering
* ETL Pipeline Development
* Data Modeling
* Data Analytics

---

## 🚀 Project Requirements

### 🛠️ Building the Data Warehouse (Data Engineering)

#### Objective

Design and implement a modern data warehouse using **SQL Server** to consolidate sales data and enable efficient analytical reporting and decision-making.

#### Specifications

* **Data Sources**:

  * Two source systems (**ERP** and **CRM**) provided as CSV files.
* **Data Quality**:

  * Perform data cleansing and resolve inconsistencies before analysis.
* **Data Integration**:

  * Combine both source systems into a unified, user-friendly analytical data model.
* **Scope**:

  * Focus exclusively on the latest available data (no historical tracking required).
* **Documentation**:

  * Provide clear and comprehensive documentation for business users and analytics teams.

---

### 📊 BI: Analytics & Reporting (Data Analysis)

#### Objective

Develop **SQL-based analytical queries** to generate insights related to:

* **Customer Behavior**
* **Product Performance**
* **Sales Trends**

These insights help stakeholders track key business metrics and support strategic, data-driven decisions.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets from ERP and CRM systems
│
├── docs/                               # Project documentation and architecture diagrams
│   ├── etl.drawio                      # ETL techniques and implementation diagrams
│   ├── data_architecture.drawio        # Overall data warehouse architecture
│   ├── data_catalog.md                 # Dataset metadata and field descriptions
│   ├── data_flow.drawio                # End-to-end data flow diagram
│   ├── data_models.drawio              # Star schema and data models
│   ├── naming-conventions.md           # Naming standards for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Raw data ingestion scripts
│   ├── silver/                         # Data cleansing and transformation scripts
│   ├── gold/                           # Analytical and reporting models
│
├── tests/                              # Data quality and validation scripts
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License details
├── .gitignore                          # Git ignored files and folders
└── requirements.txt                    # Project dependencies and requirements
```

---

This project demonstrates a structured, scalable, and industry-ready approach to data warehousing and analytics, making it an excellent addition to any **data engineering or analytics portfolio**.

