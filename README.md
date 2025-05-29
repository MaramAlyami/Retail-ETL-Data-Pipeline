# Retail-ETL-Data-Pipeline
Build an End-to-End ETL Pipeline 🎯 Objective: Design and implement a simple ETL (Extract, Transform, Load) pipeline using real-world data. The pipeline should extract data from a raw source, clean and transform it, and load it into a target destination (e.g., a CSV file, SQLite database, or simulated data warehouse). Automation using Airflow is encouraged for intermediate students.

🧩 Project Overview: Scenario (make up your own) You work as a junior data engineer at a retail analytics company. Your task is to build a data pipeline that processes daily sales data from an e-commerce site and makes it available for business analysts to use in dashboards and reports.

🗂️ Suggested Tech Stack: Python for data handling and scripting

Pandas for transformations

SQL / SQLite for loading structured data

Apache Spark for scalable data processing (if dataset is large)

Airflow for automation (optional but encouraged)

Jupyter Notebook for documentation & development

🧪 Dataset Sources Choose one public dataset from any of the following sources (or bring your own if approved by the instructor):

Kaggle Datasets
https://www.kaggle.com/datasets/abdul0haadi/e-commerce-sales-dataset-csv/data


📋 Requirements:

🔹 Phase 1: Extract Load raw data from a CSV

Validate schema and shape of raw data

Log the extraction timestamp and source

🔹 Phase 2: Transform Clean the dataset:

Handle missing values

Convert data types

Remove duplicates

Apply business logic:

Calculate KPIs like revenue = price * quantity

Create new columns (e.g., customer segment, product category)

Normalize or aggregate data if needed (e.g., group by region or date)

🔹 Phase 3: Load  the cleaned data into:

SQLite database (recommended for simplicity) OR

Write to a .csv or .parquet file (simulate a data lake)



🗃️ Deliverables: etl_pipeline.ipynb or .py script

Cleaned dataset (CSV/DB)

