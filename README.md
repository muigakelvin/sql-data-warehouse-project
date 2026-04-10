# Data Warehouse and Analytics Project

## Overview

This project is a hands-on data engineering and analytics portfolio project built to demonstrate end-to-end skills in building a modern data warehouse, from raw data ingestion to business-ready insights.

It focuses on designing a structured analytics system using SQL Server, ETL pipelines, and a Medallion Architecture approach.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture** pattern:

### Bronze Layer

* Stores raw data exactly as received from source systems
* Data is ingested from CSV files into SQL Server
* No transformations are applied at this stage

### Silver Layer

* Data cleaning and standardization
* Handling missing values, duplicates, and formatting issues
* Preparing data for analytical use

### Gold Layer

* Business-ready data models
* Star schema design (facts and dimensions)
* Optimized for reporting and analytics queries

---

## 📖 Project Overview

This project demonstrates the full lifecycle of a data warehouse system:

1. Designing a modern data warehouse architecture
2. Building ETL pipelines using SQL
3. Cleaning and transforming raw data into structured datasets
4. Creating analytical models using star schema design
5. Generating insights using SQL queries

---

## 🛠️ Tools & Technologies

* Microsoft SQL Server
* SQL Server Express (for local development)
* Docker (for containerized database environment)
* DBeaver (SQL client for querying and management)
* Git (version control)
* Draw.io (for architecture and data modeling diagrams)

---

## 🚀 Project Requirements

### Data Engineering (Warehouse Development)

#### Objective

Build a structured data warehouse that consolidates data from multiple CSV sources into a unified analytical model.

#### Key Requirements

* Load raw data from CSV files into SQL Server
* Perform data cleaning and transformation
* Integrate multiple data sources into a single model
* Design fact and dimension tables for analytics
* Focus on current dataset (no historization required)

---

### Data Analytics

#### Objective

Develop SQL-based analytics to extract insights from the warehouse.

#### Focus Areas

* Customer behavior analysis
* Product performance evaluation
* Sales trend analysis

These insights support data-driven decision-making using structured SQL queries.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                 # Raw CSV data sources
│
├── docs/                     # Architecture and design documentation
│   ├── data_architecture     # Medallion architecture design
│   ├── data_flow            # Data movement diagrams
│   ├── data_models          # Star schema design
│   ├── etl                  # ETL process diagrams
│   ├── data_catalog        # Dataset documentation
│   ├── naming-conventions  # Project naming standards
│
├── scripts/                 # SQL scripts
│   ├── bronze/              # Raw data ingestion scripts
│   ├── silver/              # Data cleaning and transformation
│   ├── gold/                # Analytical models and views
│
├── tests/                   # Data validation and testing scripts
│
├── README.md                # Project documentation
├── LICENSE                  # Project license (if applicable)
├── .gitignore               # Git ignored files
└── requirements.txt         # Project dependencies
```

---

## ☕ About This Project

This project was built by Kelvin as part of a personal learning journey in data engineering and analytics.

It reflects practical experience in:

* Data warehouse design
* ETL pipeline development
* SQL-based analytics
* Docker-based database environments
* Real-world data modeling practices

The goal of this project is to demonstrate job-ready skills in modern data engineering workflows.

---

## 🛡️ License

This project is intended for educational and portfolio purposes. You may reuse and adapt the structure for learning.

---

## 🌟 Notes

* This is a continuously evolving project
* New features such as automation, orchestration, and advanced analytics may be added over time
* The focus is on practical, production-style data engineering skills
