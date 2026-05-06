# AdventureWorks Azure Data Engineering Project

## Overview
This project demonstrates an end-to-end Azure Data Engineering pipeline built using Microsoft Azure services. The solution processes AdventureWorks business datasets through scalable ETL workflows using Medallion Architecture (Bronze, Silver, Gold layers).

The project showcases cloud-based data ingestion, transformation, storage, and analytics using Azure Data Factory, Azure Databricks, Azure Data Lake Storage, and Azure SQL Database.

---

# Architecture

## Data Flow
1. Raw datasets are ingested into Azure Data Lake Storage.
2. Azure Data Factory pipelines orchestrate data movement.
3. Azure Databricks performs data transformation using PySpark.
4. Processed datasets are stored in Bronze, Silver, and Gold layers.
5. Analytics-ready data is loaded into Azure SQL Database and Power BI dashboards.

---

# Azure Services Used

- Azure Data Factory
- Azure Databricks
- Azure Data Lake Storage Gen2
- Azure SQL Database
- Azure Key Vault
- Power BI
- Azure Storage Account

---

# Technologies Used

- PySpark
- SQL
- Python
- Azure Cloud
- ETL Pipelines
- Medallion Architecture
- Data Transformation
- Data Analytics

---

# Key Features

- End-to-end ETL pipeline implementation
- Scalable cloud-based architecture
- Incremental data loading
- Data cleaning and transformation
- Bronze, Silver, Gold layered architecture
- Analytics-ready datasets
- Data orchestration using Azure Data Factory
- PySpark-based transformations in Azure Databricks
- Cloud data storage using Azure Data Lake

---

# Medallion Architecture

## Bronze Layer
Stores raw ingested data from source systems.

## Silver Layer
Performs cleansing, validation, and transformation of raw data.

## Gold Layer
Contains business-ready curated datasets optimized for analytics and reporting.

---

# Project Structure

```bash
AdventureWorks-Azure-Data-Engineering/
│
├── datasets/
├── pipelines/
├── notebooks/
├── sql/
├── screenshots/
├── architecture/
├── README.md
```

---

# Setup Instructions

## Clone Repository

```bash
git clone https://github.com/devapanchal/AdventureWorks-Azure-Data-Engineering.git
```

---

# Azure Resources Configuration

Create the following Azure resources:

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks Workspace
- Azure SQL Database
- Azure Key Vault

---

# Data Pipeline Workflow

1. Upload datasets to Azure Data Lake.
2. Configure Azure Data Factory pipelines.
3. Execute transformation notebooks in Azure Databricks.
4. Store processed data in Silver and Gold layers.
5. Load final datasets into Azure SQL Database.
6. Visualize analytics using Power BI.

---

# Screenshots

## Architecture Diagram
Add architecture diagram screenshot here.

## Azure Data Factory Pipelines
Add pipeline screenshots here.

## Databricks Notebooks
Add notebook execution screenshots here.

## Power BI Dashboard
Add dashboard screenshots here.

---

# Learning Outcomes

Through this project, I gained hands-on exposure to:

- Azure Data Engineering workflows
- ETL pipeline development
- Data Lake architecture
- Cloud-based data transformation
- PySpark transformations
- Data orchestration using Azure Data Factory
- Azure cloud services integration

---

# Future Improvements

- CI/CD pipeline integration
- Real-time streaming pipelines
- Advanced monitoring and logging
- Automated testing
- Incremental data refresh optimization

---

# Resume Project Description

Developed an end-to-end Azure Data Engineering pipeline using Azure Data Factory, Azure Databricks, Azure Data Lake Storage, and Azure SQL Database. Implemented ETL workflows and Medallion Architecture to ingest, transform, and process AdventureWorks datasets using PySpark and SQL.

---

# Author

## Dev Panchal

- GitHub: https://github.com/devapanchal
- LinkedIn: Add your LinkedIn profile here

---