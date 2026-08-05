# Smart Water Distribution and Resource Analytics System

## 📘 Project Assignment

**Institute:** CDAC Mumbai  
**Subject:** AI Compute Platform  
**Maximum Marks:** 40  
**Title:** Smart Water Distribution and Resource Analytics System

---

## 📖 Problem Statement

A metropolitan water authority collects large volumes of data from:

- Water Treatment Plants
- Distribution Stations
- Smart Meters
- Pipeline Monitoring Systems
- Consumer Usage Records

The objective is to develop a **Smart Water Distribution Analytics Platform** using **Apache Spark** and **PySpark** to:

- Optimize water supply
- Detect leakages
- Monitor water quality
- Analyze consumption patterns
- Predict future resource demand

As a **Big Data AI Engineer**, design, implement, analyze, and deploy the complete solution using Apache Spark and PySpark.

---

## 📂 Dataset

**Dataset Name:** `Smart_Water_Distribution_Analytics.csv`

| Column Name | Description |
|-------------|-------------|
| Record_ID | Unique Record Identifier |
| Supply_Date | Water Supply Date |
| Zone | Distribution Zone |
| Distribution_Station | Distribution Station |
| Water_Source | Source of Water |
| Supply_Volume_Liters | Total Water Supplied |
| Consumption_Liters | Total Water Consumed |
| Water_Loss_Liters | Water Lost During Distribution |
| Pressure_PSI | Pipeline Pressure |
| Pipeline_ID | Pipeline Identifier |
| Leakage_Events | Number of Leakage Events |
| Water_Quality | Water Quality Category |
| PH_Value | Water pH Value |
| Turbidity_NTU | Turbidity Measurement |
| Consumer_Count | Number of Consumers |
| Maintenance_Cost | Maintenance Cost |
| System_Status | Operational Status |

---

# Questions

## Q1. Spark Environment Setup and Data Loading (4 Marks)

- Initialize SparkSession and SparkContext
- Load the CSV dataset
- Display:
  - Dataset Schema
  - First 10 Records
  - Total Number of Records
- Display descriptive statistics

---

## Q2. RDD Programming and Transformations (6 Marks)

### Perform the following:

- Create an RDD
- Apply Transformations:
  - map()
  - filter()
  - flatMap()
- Apply Actions:
  - count()
  - collect()
  - reduce()
- Calculate total water supplied for each zone using Key-Value Pair RDD

---

## Q3. Spark DataFrame Operations (8 Marks)

Perform:

- Select required columns
- Filter records
- Sort records
- Group by Zone
- Calculate:
  - Total Water Supplied
  - Total Water Consumed
  - Total Water Loss
  - Average Pipeline Pressure
  - Average Maintenance Cost

---

## Q4. Exploratory Data Analysis using Spark SQL (10 Marks)

Create a Temporary View and execute SQL queries to:

- Top 5 Zones by Water Consumption
- Zone-wise Water Loss
- Distribution Station Efficiency
- Monthly Water Supply Trend
- Monthly Water Consumption Trend
- Zones with Maximum Leakage Events
- Average pH & Turbidity by Water Source

---

## Q5. ETL Pipeline (4 Marks)

Develop an ETL pipeline to:

- Extract CSV
- Remove Duplicates
- Handle Missing Values
- Convert Data Types
- Save as Parquet

Draw the ETL Workflow.

---

## Q6. Machine Learning using Spark MLlib (4 Marks)

Choose one:

- Predict Future Water Consumption
- Predict Pipeline Leakage Risk

Implementation should include:

- Feature Selection
- Model Training
- Prediction
- Performance Evaluation

---

## Q7. Deployment using DevOps (4 Marks)

- Create GitHub Repository
- Upload Complete Project
- Explain CI/CD Pipeline using:
  - GitHub Actions
  - Jenkins
  - GitLab CI

---
