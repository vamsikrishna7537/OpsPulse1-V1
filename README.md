
# OpsPulse - Data Engineering Project

## Project Overview

OpsPulse is an end-to-end Data Engineering project
that processes NYC Yellow Taxi trip records.

The objective is to build a reliable data pipeline
that ingests, validates, transforms and stores large
datasets for analytical purposes.

## Project Objectives

- Ingest public taxi trip datasets.
- Process Parquet files using Python and Pandas.
- Perform data cleaning and validation.
- Identify missing values and duplicate records.
- Separate valid and rejected records.
- Store processed data in a database.
- Build analytical tables using SQL.
- Automate pipeline execution.
- Test and monitor pipeline reliability.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Pipeline development |
| Pandas | Data processing |
| PyArrow | Parquet file processing |
| PostgreSQL | Database |
| Git and GitHub | Version control |
| Pytest | Automated testing |
| Docker | Containerization |
| Apache Airflow | Workflow orchestration |
| Apache Spark | Distributed processing |

## Project Structure

```text
OpsPulse1-V1/
├── data/
├── src/
├── tests/
├── notebooks/
├── logs/
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Dataset

Source: NYC Taxi and Limousine Commission

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Raw datasets are not stored in this GitHub repository.

## Project Status

🚧 Currently under development.

## Learning Objectives

This project is being developed to demonstrate
practical Data Engineering skills, including
ETL pipelines, data quality, SQL, testing,
automation and deployment.
