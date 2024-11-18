# Airbnb-Data-Transformation-with-DBT 

This project demonstrates the use of **DBT** (Data Build Tool) to transform raw Airbnb data stored in **Snowflake** into analytics-ready datasets. The pipeline is orchestrated using **Dagster** for efficient workflow automation.  

---

## 🚀 Project Overview  

The primary goal of this project is to build a robust and scalable data pipeline for analyzing Airbnb listing data. It includes:  
- Data ingestion and staging in Snowflake.  
- Transforming raw data into meaningful tables using DBT.  
- Automation and orchestration of the pipeline with Dagster.  

---

## 🛠 Tools and Technologies  

- **DBT**: For data transformation and testing.  
- **Snowflake**: As the cloud data warehouse.  
- **Dagster**: For orchestrating and automating the pipeline.  
- **SQL**: For model development and data transformations.  

---

## 📂 Project Structure  

```plaintext
.
├── models/               # Contains DBT models
│   ├── staging/          # Staging models (raw to intermediate transformations)
│   ├── marts/            # Final transformed data for analytics
│   └── tests/            # Data quality tests
├── dags/                 # Dagster pipelines for orchestration
├── docs/                 # DBT documentation for the pipeline
└── README.md             # Project description and instructions
