# Olympics-Data-Pipeline-Azure

### Introduction
Here we build an end to end data pipeline for Olympics dataset using cloud services procided by Microsoft Azure.

### Architecture
![Architecture Diagram](https://github.com/KartikAnand17/Olympics-Data-Pipeline-Azure/blob/main/Architecture%20Diagram.png)

### About Dataset
The Dataset consists of various files.
1. Athletes.csv - PersonName, country, Discipline
2. Coeaches.csv - Country, Discipline, Event
3. EntriesGender.csv - Male, Female, Total
4. Medals.csv - Rank, Team_country, Gold, Silver, Bronze, Total, Rank_by_total
5. Teams.csv - TeamName, Discipline, Country, Event

### Services Used

1. **Azure Data Factory :** Azure Data Factory is a data integration tool that enables us to create, schedule and manage data pipelines for efficient data movement and transformation between various sources and destinations.

2. **Azure Data Lake Gen2 :** Data Lakes combine the capabilities of data lake with the power of Azure Blob Storage, allowing to store and analyze large volumes structured or unstructured data.
   
3.  **Azure Databricks :** Databricks is an analytics platform built on top of Apache Spark, desgined to help data engineers, data scientists collaborate on big data processing and machine learning tasks.
   
4.  **Synapse Analytics :** SQL Datawarehouse, is a cloud based analytics service. It combines big data and datawarehousing into a single integrated platform allowing the processing of large volumes of data for business intelligence and data analytics.


### Project Execution Flow
Dataset -> Data Factory -> Data Lake Gen2 -> Databricks (transformation) -> Data Lake Gen2 -> Azure Synapse -> Dashboard(Tableau, Power BI)

