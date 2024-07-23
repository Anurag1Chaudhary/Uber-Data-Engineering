# Uber-Data-Engineering GCP Project

## Introduction

Welcome to the Uber Data Analytics project! This project aims to perform comprehensive data analytics on Uber trip data using a modern data engineering stack. By leveraging Google Cloud Platform (GCP) services, Python, and various data tools, we aim to uncover insights from Uber trip records.

## Architecture

This project is built on a robust architecture that integrates multiple technologies and services to manage and analyze data efficiently. The architecture includes:

- **Google Cloud Storage**: For storing raw data and intermediate results.
- **Compute Instance**: For executing data processing tasks and running Python scripts.
- **BigQuery**: For querying and analyzing large datasets.
- **Looker Studio**: For visualizing the results and creating interactive dashboards.
- **Mage Data Pipeline Tool**: For orchestrating data workflows and transformations.

## Technology Used

- **Programming Language**: Python
- **Google Cloud Platform**:
  - **Google Storage**: Data storage
  - **Compute Instance**: Data processing
  - **BigQuery**: Data analysis
  - **Looker Studio**: Data visualization
- **Modern Data Pipeline Tool**: [Mage Data Pipeline Tool](https://www.mage.ai/)

## Dataset Used

The dataset used in this project is the **TLC Trip Record Data**. It includes:

- **Yellow and Green Taxi Trip Records**: 
  - **Pick-up and Drop-off Dates/Times**
  - **Pick-up and Drop-off Locations**
  - **Trip Distances**
  - **Itemized Fares**
  - **Rate Types**
  - **Payment Types**
  - **Driver-reported Passenger Counts**

## Project Overview

1. **Data Ingestion**: Raw Uber trip records are ingested from Google Storage into the data pipeline.
2. **Data Processing**: Python scripts and Mage Data Pipeline Tool are used to clean, transform, and enrich the data.
3. **Data Storage**: Processed data is stored in BigQuery for efficient querying and analysis.
4. **Data Analysis**: Utilize BigQuery to run SQL queries and derive meaningful insights from the data.
5. **Data Visualization**: Create interactive dashboards and visualizations using Looker Studio to present findings and support data-driven decisions.

## Getting Started

To get started with this project:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/Anurag1Chaudhary/Uber-Data-Engineering.git
