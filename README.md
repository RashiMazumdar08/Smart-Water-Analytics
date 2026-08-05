CDAC Mumbai
Subject: AI Compute Platform
Date : 05-08-2026 Maximum Marks: 40
Title : Smart Water Distribution and Resource Analytics System
Problem Statement
A metropolitan water authority collects large volumes of data from water treatment plants, distribution
stations, smart meters, pipeline monitoring systems, and consumer usage records. The authority plans
to develop a Smart Water Distribution Analytics Platform using Apache Spark to optimize water
supply, detect leakages, monitor water quality, analyze consumption patterns, and predict future resource
demand.
As a Big Data AI Engineer, design, implement, analyze, and deploy the complete solution using Apache
Spark and PySpark.
Dataset Details:
Dataset Name: Smart_Water_Distribution_Analytics.csv
Column Name Description
Record_ID Unique Record Identifier
Supply_Date Water Supply Date
Zone Distribution Zone
Distribution_Station Distribution Station
Water_Source Source of Water
Supply_Volume_Liters Total Water Supplied
Consumption_Liters Total Water Consumed
Water_Loss_Liters Water Lost During Distribution
Pressure_PSI Pipeline Pressure
Pipeline_ID Pipeline Identifier
Leakage_Events Number of Leakage Events
Water_Quality Water Quality Category
PH_Value Water pH Value
Turbidity_NTU Turbidity Measurement
Consumer_Count Number of Consumers
Maintenance_Cost Maintenance Cost
System_Status Operational Status
Q1. Spark Environment Setup and Data Loading (4 Marks)
Develop a PySpark program to perform the following tasks:
a) Initialize SparkSession and SparkContext.
b) Load the dataset Smart_Water_Distribution_Analytics.csv.
c) Display
 Dataset Schema
 First 10 Records
 Total Number of Records
d) Display descriptive statistics of numerical attributes.
Q2. RDD Programming and Transformations (6 Marks)
Create RDDs from the dataset and perform the following operations.
a) Create an RDD from the dataset.
b) Perform at least three RDD Transformations such as
 map()
 filter()
 flatMap()
c) Perform at least three RDD Actions such as
 count()
 collect()
 reduce()
d) Calculate total water supplied for each zone using Key-Value Pair RDD.
Q3. Spark DataFrame Operations (8 Marks)
Perform the following DataFrame operations.
a) Select the columns
 Zone
 Distribution_Station
 Supply_Volume_Liters
 Consumption_Liters
b) Filter records where
 Water Loss > 1000 Liters
 Leakage Events > 2
c) Sort records based on Water Loss in descending order.
d) Group records by Zone.
e) Calculate
 Total Water Supplied
 Total Water Consumed
 Total Water Loss
 Average Pipeline Pressure
 Average Maintenance Cost
Q4. Exploratory Data Analysis using Spark SQL (10 Marks)
Create a Temporary View and execute Spark SQL queries to answer the following.
a) Identify the Top 5 Zones with maximum water consumption.
b) Calculate Zone-wise Water Loss Statistics.
c) Determine the Distribution Station Efficiency.
d) Generate Monthly Water Supply Trends.
e) Generate Monthly Water Consumption Trends.
f) Find the zones with maximum leakage events.
g) Display average pH value and turbidity for each water source.
Q5. ETL Pipeline Development (4 Marks)
Design and implement an ETL Pipeline.
The pipeline should
a) Extract data from CSV.
b) Remove duplicate records.
c) Handle missing values.
d) Convert data into appropriate data types.
e) Save the processed dataset into Parquet format.
Draw the ETL workflow.
Q6. Machine Learning using Spark MLlib (4 Marks)
Develop a Machine Learning model using Spark MLlib to perform ONE of the following.
Option A
Predict future water consumption demand.
Option B
Predict pipeline leakage risk.
The implementation should include
 Feature Selection
 Model Training
 Prediction
 Performance Evaluation
Mention the evaluation metric used.
Q7. Deployment using DevOps Tools (4 Marks)
Perform the following deployment tasks.
a) Create a GitHub repository and upload the complete project.
b) Explain the CI/CD pipeline using GitHub Actions/Jenkins/GitLab CI.
