# Data Engineering Pipeline for Uber Data Analysis

![model_diagram](https://github.com/SunGajiwala/uber-data-engineering-etl-pipeline/blob/main/architecture.jpg?raw=true)

This repository contains code and documentation for building a robust data engineering pipeline to analyze Uber data. The pipeline is designed using Google Cloud Platform (GCP) services including BigQuery and Looker for data storage, processing, and visualization.

## Overview

Uber generates vast amounts of data from various sources including ride requests, driver activities, and user interactions. Analyzing this data can provide valuable insights for optimizing operations, improving user experience, and making data-driven decisions.

The data engineering pipeline outlined in this repository aims to:

1. Ingest raw Uber data from a csv file
2. Extract Process and Transform data using [Mage-AI](https://www.mage.ai)
3. Store Transformed data to google Cloud Storage
4. Create meaningful visualizations and dashboards using Looker
5. Enable stakeholders to explore and gain insights from the data

# Technologies Used

-> Google Cloud Platform (GCP)
*  Compute Engine: For running Mage-AI
*  BigQuery: For data warehousing and analytics
*  Cloud Storage: For storing raw data files
  
-> Looker: For data visualization and exploration

-> Make-AI: To build ETL data engineering pipeline

# Looker Dashboard

Access the looker dashboard using this [uber_data_analytics](https://lookerstudio.google.com/reporting/b7ed88eb-960f-4d63-a7b5-7aec3a9ebb5d)
