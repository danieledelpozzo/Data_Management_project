# PySpark TPCx-BB Benchmark Query Implementation

## Overview
This project implements a subset of the TPCx-BB (BigBench) benchmark queries using **Apache Spark** and **PySpark DataFrames**.  
The goal is to demonstrate how SQL-based analytical queries from the TPCx-BB suite can be translated into PySpark DataFrame operations for distributed processing on large datasets.


TPCx-BB is a well-known benchmark designed to evaluate big data analytics and machine learning performance in a distributed environment. In this project, I focused on **data manipulation, filtering, aggregation, and joining operations** using PySpark.

---

## Features
- Translate and implement SQL queries from TPCx-BB into PySpark DataFrame operations.
- Handle large datasets in **parquet format** efficiently using Spark.
- Demonstrate core PySpark operations:
  - DataFrame creation and inspection
  - Column and row operations (add, rename, delete, update)
  - Filtering and conditional logic
  - Joins and aggregations
  - Aliases and orderBy operations
  - Handling missing values 
- Implemented queries include:
  - Query 0: Count of items sold by category in selected stores
  - Query 7: High-priced item sales per state with filtering and aggregation
  - Query 9: Conditional sales aggregation based on customer demographics
  - Query 20: Customer segmentation with returns ratio calculations

---

## Dataset
The project uses **TPCx-BB dataset tables** stored in parquet format:
- store_sales
- item
- customer
- customer_address
- store
- customer_demographics
- date_dim
- store_returns

**Note:** Only the subset of tables needed for the queries is loaded in this repository.

---

## Technologies Used
- Apache Spark 3.x
- PySpark SQL & DataFrame API
- Python 
- Jupyter Notebook for interactive exploration
- Parquet files for efficient dataset storage

---

## Ownership

This project was created as part of the Data Management course at Università della Svizzera italiana (USI).

