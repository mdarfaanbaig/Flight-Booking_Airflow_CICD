# 🚀 Flight Booking Data Pipeline  

## Overview  
This project automates the processing of flight booking data using **Apache Airflow**, **PySpark**, and **Google Cloud Services**. The pipeline transforms raw data and loads it into **BigQuery** for business insights.  

## Tech Stack  
- **Orchestration**: Apache Airflow (Composer)  
- **Processing**: PySpark (Dataproc Serverless)  
- **Storage**: Google Cloud Storage (GCS), BigQuery  
- **CI/CD**: GitHub Actions  
- **Version Control**: GitHub  

## Project Workflow  
1. **Airflow DAG** triggers a PySpark job on **Dataproc Serverless**.  
2. **PySpark Job** processes flight booking data and writes the transformed output to **BigQuery**.  
3. **CI/CD Pipeline** automates deployment of Airflow DAGs and Spark jobs to Dev/Prod using **GitHub Actions**.  


