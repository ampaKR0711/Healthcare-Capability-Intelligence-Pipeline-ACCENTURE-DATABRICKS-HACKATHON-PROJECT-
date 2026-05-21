# Healthcare Capability Intelligence Pipeline using Databricks

## Databricks Accenture Challenge Hackathon 2026  
### Theme: Data Engineering

---

## Team Information

| Field | Details |
|---|---|
| Team Name | KRIPA |
| University | KIIT University |
| Hackathon | Databricks Accenture Challenge Hackathon 2026 |
| Theme | Data Engineering |

---

## Overview

This project is a healthcare analytics and intelligent document parsing pipeline developed using Databricks, Apache Spark, Delta Lake, SQL Analytics, and Power BI.

The objective of the project is to process healthcare treatment data, extract meaningful healthcare capabilities from unstructured text, and visualize analytical insights through dashboards.

This project was created as part of the Databricks Accenture Challenge Hackathon 2026 under the Data Engineering theme.

---

## Problem Statement

Healthcare datasets often contain unstructured treatment descriptions and medical information that are difficult to analyze directly. Manual interpretation of healthcare capabilities is inefficient and time-consuming.

This project demonstrates how Databricks can be used to:

- Process healthcare datasets
- Perform intelligent healthcare feature extraction
- Store processed data using Delta Lake
- Run SQL-based analytics
- Create interactive dashboards
- Generate structured healthcare insights

---

## Solution Overview

The project processes healthcare treatment datasets using Databricks notebooks and Apache Spark.

A custom Intelligent Document Parsing (IDP) logic was implemented using Python and Spark UDFs to automatically identify healthcare-related capabilities such as Surgery, Cardiology, Emergency Care, Imaging, Neurology, and Radiology from free-form treatment descriptions.

The processed dataset was stored using Delta Lake tables, analyzed using SQL queries, and finally connected to Power BI for dashboard visualization.

---

## Technologies Used

- Databricks
- Apache Spark
- Python
- Delta Lake
- SQL
- Power BI
- Kaggle Healthcare Dataset

---

## Project Workflow

```text
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
```

---

## Main Features

- Healthcare dataset preprocessing
- Intelligent healthcare capability extraction
- Delta Lake integration
- SQL analytics queries
- Power BI dashboard visualization
- Interactive healthcare analysis
- KPI-based healthcare insights

---

## Intelligent Document Parsing (IDP)

The project uses custom Python logic and Spark UDFs to identify healthcare-related features such as:

- Surgery
- Cardiology
- Emergency Care
- Radiology
- Imaging
- Neurology
- Dialysis
- Orthopedic Care

These healthcare capabilities are extracted from free-form healthcare treatment descriptions and stored in a structured column called:

```text
detected_features
```

This converts unstructured healthcare text into structured analytical information.

---

## SQL Analytics

The following SQL analyses were performed:

- Treatment type distribution
- Healthcare capability analysis
- Average treatment cost analysis
- Healthcare feature frequency analysis
- Total healthcare expenditure analysis

Visualizations such as pie charts and bar charts were generated directly using Databricks SQL.

---

## Dashboard Features

The Power BI dashboard includes:

- Treatment distribution chart
- Healthcare feature pie chart
- Cost analysis charts
- KPI cards
- Interactive filters
- Healthcare analytics visualizations

---

## Databricks Components Used

- Databricks Notebooks
- Apache Spark
- Delta Lake
- Databricks SQL Warehouse

---

## Why Databricks

Databricks provides an integrated environment for:

- Large-scale data processing
- Spark-based analytics
- Collaborative notebook workflows
- Delta Lake storage
- SQL analytics
- Scalable healthcare data engineering workflows

This makes Databricks highly suitable for healthcare analytics and intelligent document parsing applications.

---

## What Was Built During the Hackathon

The following components were implemented during the hackathon:

- Dataset ingestion pipeline
- Data preprocessing workflow
- Intelligent healthcare capability extraction
- Delta Lake integration
- SQL analytics queries
- Power BI dashboard
- Healthcare analytics visualizations

Public healthcare datasets were used as input data.

---

## Databricks-Specific Implementation Details

The project was implemented using Databricks notebooks with Python and Apache Spark.

Workflow included:

1. Dataset loading into Spark DataFrames
2. Missing value handling
3. Intelligent parsing using Python UDFs
4. Delta Lake table creation
5. SQL analytics execution
6. CSV export for Power BI integration

The notebook workflow was organized into:

- Dataset loading
- Preprocessing
- IDP logic
- Delta storage
- SQL analytics
- Dashboard preparation

---

## Technical Challenges Faced

### Schema Mismatch Issues

Delta table schema conflicts occurred during overwrite operations.

### Solution

Used overwrite schema handling during Delta Lake table creation.

---

### Missing Value Handling

Healthcare datasets contained incomplete records.

### Solution

Used Spark DataFrame preprocessing and fillna() operations.

---

### Feature Extraction Accuracy

Different treatment descriptions required proper healthcare keyword detection.

### Solution

Implemented rule-based healthcare feature extraction using Spark UDFs.

---

## Performance & Scalability Considerations

- Apache Spark enabled scalable healthcare data processing
- Delta Lake improved structured storage reliability
- Spark DataFrame transformations improved processing efficiency
- The architecture can be extended for:
  - Real-time streaming
  - Machine learning models
  - Cloud deployment
  - Large-scale healthcare analytics

---

## How to Run the Project

### Requirements

- Databricks Community Edition
- Python Notebook
- Apache Spark
- Power BI Desktop

---

### Steps

#### 1. Open Databricks Workspace

Create a new Python notebook.

#### 2. Upload Dataset

Upload healthcare CSV dataset into Databricks workspace.

#### 3. Run Notebook Cells Sequentially

Run:
- Dataset loading
- Preprocessing
- Intelligent parsing
- Delta table creation
- SQL analytics

#### 4. Export Processed Dataset

Export processed dataset as CSV.

#### 5. Open Power BI

Import exported CSV into Power BI.

#### 6. Create Dashboard

Build healthcare analytics visualizations.

---

## Performance Highlights

- Efficient Spark DataFrame processing
- Structured Delta Lake storage
- SQL-based analytical querying
- Interactive Power BI visualization workflow
- Modular notebook pipeline

---

## Future Improvements

- Real-time healthcare data streaming
- Machine learning prediction models
- AI-based medical recommendation systems
- NLP-powered healthcare text understanding
- Cloud deployment
- Advanced healthcare KPI monitoring

---

## Conclusion

This project demonstrates a simple but effective healthcare data engineering workflow using Databricks, Apache Spark, Delta Lake, SQL analytics, and Power BI.

The project successfully transforms unstructured healthcare treatment data into structured analytical insights through Intelligent Document Parsing and analytics workflows.

---

## Hackathon Submission Information

| Category | Details |
|---|---|
| Hackathon | Databricks Accenture Challenge Hackathon 2026 |
| Theme | Data Engineering |
| Project Type | Healthcare Analytics & Intelligent Document Parsing |
| Platform | Databricks Community Edition |

---

## Author

### Team KRIPA

Databricks Accenture Challenge Hackathon 2026
