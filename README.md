Healthcare Capability Intelligence Pipeline using Databricks
Databricks Accenture Challenge Hackathon 2026
Theme: Data Engineering
Team Information
Field	Details
Team Name	KRIPA
University	KIIT University
Hackathon	Databricks Accenture Challenge Hackathon 2026
Theme	Data Engineering
Project Overview

Healthcare datasets often contain unstructured treatment descriptions and medical information that are difficult to analyze directly. Manual interpretation of healthcare capabilities is time-consuming, inefficient, and error-prone.

This project implements an end-to-end healthcare analytics and intelligent document parsing pipeline using Databricks, Apache Spark, Delta Lake, SQL analytics, and Power BI.

The system processes healthcare treatment datasets, extracts meaningful healthcare-related capabilities from free-form text, stores the processed data in Delta Lake tables, performs SQL-based analytics, and visualizes insights through an interactive Power BI dashboard.

Problem Statement

Healthcare treatment datasets contain large amounts of unstructured medical information that cannot be efficiently analyzed using traditional manual approaches.

Hospitals and healthcare organizations require intelligent systems that can:

Process healthcare datasets efficiently
Extract meaningful healthcare capabilities from text
Generate structured analytical insights
Support healthcare decision making using data analytics

The project addresses this challenge by building a healthcare capability intelligence pipeline using Databricks.

Solution Overview

The project was implemented using Databricks notebooks and Apache Spark.

Healthcare datasets were loaded into Spark DataFrames and preprocessed to handle missing values and prepare structured text columns for analytics.

A custom Intelligent Document Parsing (IDP) mechanism was implemented using Python and Spark UDFs to automatically identify healthcare-related capabilities such as:

Surgery
Cardiology
Emergency Care
Neurology
Radiology
Imaging
Dialysis

The extracted capabilities were stored in a new column called:

detected_features

The processed data was stored using Delta Lake tables and analyzed using Databricks SQL queries.

Finally, Power BI was connected to the processed dataset to create an interactive healthcare analytics dashboard.

Architecture / Workflow
Healthcare CSV Dataset
        ↓
Databricks Notebook (PySpark)
        ↓
Data Cleaning & Preprocessing
        ↓
Intelligent Document Parsing (IDP)
        ↓
Delta Lake Storage
        ↓
SQL Analytics
        ↓
Power BI Dashboard
Technologies Used
Technology	Purpose
Python	Data preprocessing
Apache Spark	Large-scale data processing
Databricks	Notebook and analytics platform
Delta Lake	Processed data storage
SQL	Analytics queries
Power BI	Dashboard visualization
Databricks Components Used

✅ Databricks Notebooks
✅ Apache Spark
✅ Delta Lake
✅ Databricks SQL Warehouse

Key Features
Healthcare dataset preprocessing using Apache Spark
Intelligent healthcare capability extraction from unstructured text
Rule-based Intelligent Document Parsing (IDP)
Delta Lake integration for structured storage
SQL-based healthcare analytics
Treatment distribution analysis
Healthcare cost analysis
Interactive Power BI dashboard
KPI cards and healthcare insights visualization
Dataset Information

The project uses a healthcare treatment dataset containing:

Treatment descriptions
Healthcare costs
Patient-related healthcare information
Medical capability references

The dataset was processed inside Databricks using Spark DataFrames.

Intelligent Document Parsing (IDP)

The core functionality of this project is Intelligent Document Parsing.

Using Python and Spark UDFs, the system automatically extracts healthcare capabilities from free-form treatment descriptions.

Example extracted features include:

Surgery
Cardiology
Emergency Care
Neurology
Imaging
Orthopedic Care

This converts unstructured healthcare text into structured analytical information.

SQL Analytics Performed

The following analytics were performed using Databricks SQL:

Treatment Distribution Analysis

Analyzed frequency of detected healthcare capabilities.

Cost Analysis

Calculated average healthcare treatment costs.

Feature-Based Analytics

Compared healthcare costs across different healthcare capabilities.

Visualization

Generated:

Pie charts
Bar charts
Analytical summaries
Power BI Dashboard

The processed dataset was connected to Power BI to create an interactive healthcare analytics dashboard.

Dashboard includes:

KPI cards
Treatment distribution charts
Healthcare capability visualization
Cost analysis charts
Interactive filters
Why Databricks is a Good Fit

Databricks provides:

Integrated Spark-based analytics
Scalable data engineering workflows
Unified notebook environment
SQL analytics support
Delta Lake storage
Collaborative development environment

These features make Databricks highly suitable for healthcare analytics and intelligent data processing workflows.

What Was Built During the Hackathon

The following components were implemented during the hackathon:

Dataset ingestion pipeline
Data preprocessing workflow
Intelligent healthcare capability extraction
Delta Lake integration
SQL analytics queries
Power BI dashboard
Healthcare analytics visualizations

Public healthcare datasets were used as input data.

Databricks-Specific Implementation Details

The project was implemented using Databricks notebooks with Python and Apache Spark.

Workflow included:

Dataset loading into Spark DataFrames
Missing value handling
Intelligent parsing using Python UDFs
Delta Lake table creation
SQL analytics execution
CSV export for Power BI integration

The notebook was organized into:

Dataset loading
Preprocessing
IDP logic
Delta storage
SQL analytics
Dashboard preparation
Technical Challenges Faced
Schema Mismatch Issues

Delta table schema conflicts occurred during overwrite operations.

Solution

Used overwrite schema handling during Delta table creation.

Missing Value Handling

Healthcare datasets contained incomplete records.

Solution

Used Spark DataFrame preprocessing and fillna() operations.

Feature Extraction Accuracy

Different treatment descriptions required proper healthcare keyword detection.

Solution

Implemented rule-based healthcare feature extraction using Spark UDFs.

Performance & Scalability Considerations
Apache Spark enabled scalable data processing
Delta Lake improved structured storage reliability
Spark DataFrame transformations improved processing efficiency
The architecture can be extended for:
Real-time streaming
Machine learning models
Cloud deployment
Large-scale healthcare analytics
How to Run the Project
Requirements
Databricks Community Edition
Python Notebook
Apache Spark
Power BI Desktop
Steps
1. Open Databricks Workspace

Create a new Python notebook.

2. Upload Dataset

Upload healthcare CSV dataset into Databricks workspace.

3. Run Notebook Cells Sequentially

Run:

Dataset loading
Preprocessing
Intelligent parsing
Delta table creation
SQL analytics
4. Export Processed Dataset

Export processed dataset as CSV.

5. Open Power BI

Import exported CSV into Power BI.

6. Create Dashboard

Build healthcare analytics visualizations.

Future Improvements
Real-time healthcare streaming pipeline
Machine learning-based prediction system
NLP-based medical text understanding
Cloud deployment
Advanced healthcare KPI monitoring
AI-powered healthcare recommendation systems
Conclusion

This project demonstrates a simple but effective healthcare data engineering workflow using Databricks, Apache Spark, Delta Lake, SQL analytics, and Power BI.

The project successfully transforms unstructured healthcare treatment data into structured analytical insights through Intelligent Document Parsing and data analytics workflows.

Hackathon Submission Information
Category	Details
Hackathon	Databricks Accenture Challenge Hackathon 2026
Theme	Data Engineering
Project Type	Healthcare Analytics & Intelligent Document Parsing
Platform	Databricks Community Edition
Thank You

Healthcare Capability Intelligence Pipeline using Databricks
Databricks Accenture Challenge Hackathon 2026
