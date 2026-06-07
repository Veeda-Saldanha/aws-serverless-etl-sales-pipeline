# AWS Serverless ETL Pipeline for Sales Data Processing

## 📌 Project Overview

This project demonstrates an end-to-end serverless ETL pipeline built on AWS for ingesting, transforming, storing, and analyzing sales data.

The pipeline extracts sales data from an external API, processes and cleans the data using AWS Lambda and Python, stores the processed data in Amazon S3, catalogs the data using AWS Glue Crawler, and performs analytics using Amazon Athena.

---

## 🏗️ Architecture

```text
External API
      ↓
AWS Lambda
      ↓
Amazon S3
      ↓
AWS Glue Crawler
      ↓
Amazon Athena
      ↓
Business Insights
```

---

## 🛠️ Technologies Used

- AWS Lambda
- Amazon S3
- AWS Glue
- Amazon Athena
- AWS IAM
- Python
- Pandas
- SQL
- Parquet

---

## 🔄 ETL Workflow

### 1. Data Extraction
- Extract sales data from an external API using Python.

### 2. Data Transformation
- Remove duplicate records.
- Handle missing values.
- Standardize and clean data using Pandas.

### 3. Data Loading
- Store processed data in Amazon S3.
- Convert data into analytics-friendly formats.

### 4. Data Cataloging
- Configure AWS Glue Crawler.
- Automatically create metadata tables.

### 5. Data Analytics
- Query data using Amazon Athena.
- Generate business insights and reports.

---

## ✨ Key Features

- Serverless ETL Pipeline
- Automated Data Processing
- Data Cleaning & Transformation
- Data Validation
- AWS Glue Data Catalog Integration
- SQL Analytics with Athena
- Cloud-Based Data Engineering

---

## 📊 Business Insights Generated

- Monthly Sales Trends
- Top Performing Products
- Category-wise Sales Analysis
- Sales Performance Reporting

---

## 🚀 Skills Demonstrated

- Data Engineering
- ETL Pipeline Development
- SQL Query Optimization
- AWS Cloud Services
- Data Transformation
- Data Validation
- Data Warehousing Concepts
- Serverless Computing
- Data Analytics

---

## 📂 Repository Structure

```text
aws-serverless-etl-sales-pipeline/
│
├── README.md
├── lambda/
│   └── lambda_function.py
├── screenshots/
├── architecture/
└── sample-data/
```

---

## 👩‍💻 Author

**Veeda Saldanha**

- GitHub: https://github.com/Veedasaldanha
- LinkedIn: https://www.linkedin.com/in/veeda-saldanha-a6b1271b3
