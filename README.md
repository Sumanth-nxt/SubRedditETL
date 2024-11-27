# SubReddit ETL project
------------

## Overview
-----------

In this project I have written python scripts to extract, transform, and load (ETL) Reddit data into a Redshift data warehouse. Also additional tools such as Apache Airflow, Celery, Docker, PostgreSQL, Amazon S3, AWS Glue, Amazon Athena, and Amazon Redshift are used to create a Data warehouse on cloud.

## Architecture
-------------
- *insert system design image here

### Components

- **Reddit API**: Data source
- **Apache Airflow & Celery**: Orchestrates ETL pipeline.
- **PostgreSQL**: Temporary storage and metadata management.
- **Amazon S3**: Raw data storage.
- **AWS Glue**: Data cataloging and ETL jobs.
- **Amazon Athena**: SQL transformations.
- **Amazon Redshift**: Data warehousing and analytics.

## Prerequisites
-------------

- **AWS Account**: With S3, Glue, Athena, and Redshift.
- **Reddit API Credentials**: Register as developer get access IDs and tokens
- **Docker Installation**
- **Python 3.9 or Higher**
