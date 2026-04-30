📊 Big Data Analytics Project

📌 Overview

This project demonstrates practical implementation of Big Data tools including:
1. Apache Sqoop
2. Apache Pig
3. Apache Hive

The objective is to showcase data ingestion, processing, and analysis using the Hadoop ecosystem.

🧰 Technologies Used
* Hadoop (HDFS & YARN)
* Apache Sqoop
* Apache Pig (Pig Latin)
* Apache Hive (HiveQL)
* MySQL (RDBMS)

📁 Project Structure

├── sqoop/

│   ├── import_single_table
│   ├── import_all_tables
│   └── export_table
│
├── pig/

│   ├── load_data
│   ├── foreach_operations
│   ├── group_by
│   ├── order_by
│   └── filter_data
│
├── hive/

│   ├── internal_table
│   ├── external_table
│   └── partitioning
│
└── README.md

🚀 Features & Implementation

🔹 1. Apache Sqoop (Data Transfer)
Import data from MySQL to HDFS
Import all tables with exclusions
Export processed data back to MySQL

🔹 2. Apache Pig (Data Processing)
Performed data transformations using Pig Latin:
Load data into relations
Use FOREACH for transformations
Perform GROUP BY aggregations
Apply ORDER BY sorting
Filter records using conditions

🔹 3. Apache Hive (Data Warehousing)
Created databases and tables
Worked with:
Internal Tables (Managed)
External Tables
Implemented:
Static Partitioning
Dynamic Partitioning

📊 Key Concepts Covered

* Data Import/Export using Sqoop
* Data Transformation using Pig
* SQL-like Querying using Hive
* Partitioning for performance optimization
* Big Data pipeline integration

📈 Learning Outcomes
* Hands-on experience with Big Data tools
* Understanding of ETL pipeline in Hadoop
* Improved data processing and querying skills
* Practical exposure to real-world data workflows
