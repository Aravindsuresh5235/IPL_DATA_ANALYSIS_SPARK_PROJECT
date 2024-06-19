# IPL_DATA_ANALYSIS_SPARK_PROJECT

## Introduction
This project analyzes IPL (Indian Premier League) cricket data using a data pipeline. The data is taken from a dataset, stored in an S3 bucket, and transformed using Apache Spark. The project is built on Databricks.
## Architecture
![Architecture](https://github.com/Aravindsuresh5235/IPL_DATA_ANALYSIS_SPARK_PROJECT/assets/80466501/dc9dfb09-cfb5-4a26-8fa5-1956574aabc1)
The diagram shows the data flow from collection to storage, processing, analysis, and visualization.

## Dataset/API
The dataset includes information on all IPL matches up to the 2017 season.

## Data Source
 Amazon S3 

## Technologies Used
Apache Spark: For efficient data processing.
SQL Spark: For powerful data querying.
Matplotlib & Seaborn: For creating visualizations.
Databricks: For managing the data lifecycle, including setting up clusters and collaborative notebooks.

## Project Execution Flow

1. Data Ingestion: Fetch the IPL dataset and store it in an S3 bucket.

2. Cluster Setup: Set up a Databricks cluster.

3. Data Loading: Load the raw data from S3 into Databricks.

4. Data Processing: Clean, transform, and enrich the data using Apache Spark.

5. Clean: Fix missing values, correct data types, and remove duplicates.

6. Transform: Normalize and aggregate the data.

7. Data Analysis: Analyze the data using SQL Spark to gain insights into player performances, 
                  team statistics, and match outcomes, and to identify trends and patterns 
                  across different seasons.

8. Data Visualization: Create visualizations using Matplotlib and Seaborn to show key insights 
                       through graphs and charts, and develop interactive dashboards for data 
                       exploration.
