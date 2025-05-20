# Retail Sales Analysis and Optimization using Microsoft Azure

## Overview
This project is centered around developing Extract, Transfor and Load (ETL) pipeline showcasing the advanced capabilities of Microsoft Azure. This pipeline effucently reterives data from Kaggla API, performs neccessart trrabsformations usinf Azure Databricks and Azure Data Factory, and stores it in Azure Data Lake containers. Then using Azure Synapse and Power BI a report is created. Additionally, the pipeline features a sales analysis component using PySpark within Azure Databricks, enabling comprehensive examination and analysis of sales data. The final analyzed data is securely stored in a SQL layer for subsequent use. This holistic solution streamlines the data processing workflow and provides actionable insights from the transformed and analyzed data, enhancing decision-making processes.

## Dataset

The dataset used in this prokect contains detailed information of sales transactions using the AdventureWorks dataset provided by Microsoft. 

## Dataflow

* Extract Data: Retrive the data from Kaggle API and ingest it into the Azure Data Factory.

* Transform Data: The data is then transformed from bronze layer stored in Azure blog to silver layer using Microsoft Azure Databricks.

* Load Data: The data is silver layer. Using Microsoft Azure Synapse the data is transformed into Gold layer and then connected to Power BI to create dashboard for the stakeholders.

![plot](https://github.com/Shaw1390/Adventureworks/blob/main/Img/Screenshot%202025-05-19%20174048.jpg?raw=true)

## Dashboard 

