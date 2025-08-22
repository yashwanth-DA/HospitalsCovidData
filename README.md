# HospitalsCovidData

---

## Overview
**HospitalsCovidData** project demonstrates building **scalable, automated data pipelines** to ingest, transform, and store COVID-19 hospital data for predictive reporting.  

The architecture integrates multiple data sources, performs transformations, and stores the data in both **Data Warehouses** and **Data Lakes** for analytics and reporting purposes.

---

## Architecture
The project workflow follows this architecture:

![ADF architecture](https://github.com/user-attachments/assets/5ed39f6a-1eba-4b99-911f-4744255bc8ac)


1. **Data Sources**  
   - Data is collected from reliable public sources such as **ECDC** and the **European Statistical System**.  

2. **Data Integration, Transformation, and Orchestration**  
   - **Azure Data Factory (ADF)** orchestrates the ingestion and transformation pipelines.  
   - **Azure Databricks** and **Spark** are used to process and clean the data.  
   - Transformed data is structured for downstream consumption.  

3. **Data Storage**
   - **Data Warehouse (SQL Database)**: Stores structured, analytics-ready data.  
   - **Data Lake (ADLS)**: Stores raw and transformed data for flexible analytics and archival purposes.  

---

## Key Features
- **Automated Data Ingestion** from multiple public sources  
- **Data Transformation** using Databricks and Spark for cleaning, processing, and structuring data  
- **Pipeline Orchestration** via ADF for scheduling and monitoring  
- **Dual Storage** in **Data Warehouse** and **Data Lake** for versatile data access  
- **Analytics & Reporting** ready datasets for dashboards, predictive models, and research  

---

## Technologies Used
- **Azure Data Factory (ADF)** – Orchestrate ETL workflows  
- **Azure Databricks & Spark** – Data transformation and processing  
- **Azure Data Lake Storage (ADLS)** – Store raw and transformed datasets  
- **Azure SQL Database** – Structured storage for analytics and reporting  

---
## Power BI Reports
![PB 1](https://github.com/user-attachments/assets/c119b8c5-7e2f-4de4-a054-2242f26ef91b)

![PB 2](https://github.com/user-attachments/assets/c4ac09f9-95c5-4508-9ab3-ff94e4958f2c)





