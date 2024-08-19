# Walmart-Data-Ingestion-into-BigQuery
# Overview:
This project outlines the implementation of a data pipeline for ingesting Walmart data into BigQuery. The pipeline utilizes Python, Airflow, GCP Storage, and BigQuery to create dimension and staging tables, followed by an upsert operation into a fact table using a BigQuery Merge query.

# Tech Stack:

Python
Airflow
GCP Storage
BigQuery
Data Flow:

Data extraction from Walmart source
Data loading into GCP Storage
Dimension and staging table creation using Airflow and BigQuery
Data loading into dimension and staging tables
Fact table upsert using BigQuery Merge query
Architecture:
[Include architecture diagram]

Airflow DAG:
[Include Airflow DAG diagram]

