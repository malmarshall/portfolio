# Project 3 - End-to-End Pipeline (API --> SQL --> ML --> Dashboard)
#### Dataset: CDC API or Census API

## Goal: Build a fill data pipeline that ingests data from an API, stores it in SQL, trains a model, and visualizes results. 

# Outline
1. Data Ingestion
   - Use Python to call API
   - Extract JSON
   - Normalize into tables
2. SQL Storage
   - Create database (PostgreSQL or SQLite)
   - Create tables
   - Insert data
   - Write SQL queries to validate
3. Data Cleaning & Transformation
   - Handle missing values
   - Standardize column names
   - Create dervied features
4. Modeling
   - Choose a simple ML task such as:
       - Predicting a demographic indicator
       - Clustering counties by socioeconomic factors
       - Predicting environmental exposure levels
6. Dashboard
   - Use Power BI, Tableau, or Plotly Dash to visualize:
       - Trends
       - Geographic patterns
       - Model predictions
8. Automation (Optional)
   - Schedule API pulls
   - Automate SQL updates
   - Refresh dashboard



 ## Deliverables
 - ETL script
 - SQL schema
 - ML notebook
 - Dashboard
 - README with architecture diagram
