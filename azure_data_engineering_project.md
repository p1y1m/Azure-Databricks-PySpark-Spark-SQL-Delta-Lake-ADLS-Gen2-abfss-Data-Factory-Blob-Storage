# Azure End-to-End Data Engineering with Databricks, Delta Lake and ADLS Gen2

The integration of cloud-native data engineering services enables the design of scalable, decoupled, and production-ready data platforms. In this project, I designed and implemented an end-to-end data pipeline in Azure, combining ingestion, transformation, storage, and orchestration using enterprise-grade services and best practices.

## Overview

- Designed a full data ingestion layer using Azure Data Factory, implementing a Copy Data pipeline to orchestrate movement of raw CSV data into structured storage zones  
- Configured Azure Blob Storage / ADLS Gen2 as the data lake foundation, managing containers, hierarchical namespaces, and ABFSS access patterns  
- Deployed Azure Databricks and engineered distributed data processing workflows using PySpark DataFrames and Spark SQL  
- Implemented secure access control via Azure RBAC and cluster-level Spark configuration, resolving authentication and storage access constraints  
- Diagnosed and remediated ADLS Gen2 incompatibilities (Soft Delete / Data Protection conflicts with DFS endpoint), enabling stable read/write operations  
- Built transformation pipelines generating partitioned outputs and optimized datasets for downstream analytics  
- Created temporary and persistent Spark SQL views to compute aggregated metrics (e.g., customer spend analysis)  
- Implemented Delta Lake tables to ensure ACID compliance, schema enforcement, and scalable analytics over large datasets  
- Registered external Delta tables in the metastore to enable reusable SQL-based querying and interoperability  
- Developed Databricks Jobs for production execution, resolving compute quota limitations through Single Node cluster optimization  
- Applied FinOps practices by monitoring Azure Cost Management, identifying hidden costs (NAT Gateway, networking, compute), and eliminating unnecessary resources  
- Executed full resource lifecycle management, including exporting artifacts, decommissioning Databricks infrastructure, and retaining only cost-efficient services  

## Architecture Highlights

This project demonstrates practical implementation of modern data architecture patterns, including lakehouse design, distributed processing, secure data access, and cost-aware cloud engineering. It also highlights real-world troubleshooting across IAM, networking, and storage layers, which are critical for production environments.

## Key Technologies

- Azure Data Factory (ADF)  
- Azure Databricks  
- PySpark / Spark SQL  
- Delta Lake  
- Azure Data Lake Storage Gen2 (ADLS Gen2)  
- Azure Blob Storage  
- ABFSS protocol  
- Azure RBAC / IAM  
- FinOps / Cost Optimization  

## GitHub

https://github.com/p1y1m/Azure-Databricks-PySpark-Spark-SQL-Delta-Lake-ADLS-Gen2-abfss-Data-Factory-Blob-Storage/blob/main/Data%20Management.ipynb
