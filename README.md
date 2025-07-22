# Data Engineering Project: Cloud Data Pipeline

## Overview
This project demonstrates a modern data engineering pipeline that integrates AWS, Snowflake, Power BI, SQL, Python, AWS Glue, and Apache Airflow.

## Tech Stack
- **AWS S3**: For raw and processed data storage
- **AWS Glue**: For ETL jobs and schema cataloging
- **Snowflake**: Cloud data warehouse
- **Apache Airflow**: DAG scheduling and orchestration
- **Python**: Scripting and transformation logic
- **SQL**: Data transformation and modeling in Snowflake
- **Power BI**: Dashboarding and business insights

## Folder Structure
```
data/
  raw/              # Raw data files
  processed/        # Cleaned data outputs

scripts/
  python/           # Python scripts for ETL & Glue

sql/                # SQL scripts for Snowflake

airflow/
  dags/             # Airflow DAGs

aws/
  glue_jobs/        # AWS Glue scripts and configs

powerbi/            # PBIX files or visual templates

snowflake/
  ddl/              # Snowflake schema, stage, and table definitions

notebooks/          # Jupyter notebooks for exploration
```

## Use Cases
- Ingest CSV files from AWS S3
- Transform using AWS Glue or Python scripts
- Load into Snowflake
- Schedule via Airflow
- Visualize in Power BI

## Getting Started
1. Upload data to `data/raw/`
2. Configure Glue jobs in `aws/glue_jobs/`
3. Create Snowflake tables using `snowflake/ddl/`
4. Run Airflow DAGs in `airflow/dags/`
5. Build Power BI dashboards from Snowflake queries

---

*This project is meant for educational and portfolio purposes.*
