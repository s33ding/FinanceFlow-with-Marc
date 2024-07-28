# FinanceFlow with Marc
## Project Overview

**finance_flow_with_marc** is a data pipeline project designed to fetch, process, and store stock prices from the Yahoo Finance API. The pipeline uses Apache Airflow for orchestration, Minio for object storage, Spark for data processing, PostgreSQL for the data warehouse, Slack for notifications, and Metabase for data visualization.

## Pipeline Components

- **Yahoo Finance API**: Source of stock price data
- **is_api_available**: Checks API availability
- **fetch_stock_prices**: Fetches stock price data
- **store_prices**: Stores data in Minio
- **format_prices**: Formats data using Spark
- **get_formatted_csv**: Retrieves formatted data from Minio
- **load_to_dw**: Loads data into PostgreSQL
- **Notifications**: Sends notifications to Slack
- **Metabase**: Visualizes data in PostgreSQL

## Technology Stack

- Apache Airflow
- Minio
- Apache Spark
- PostgreSQL
- Slack
- Metabase
- Astro

## Installation

Astro: Astro is a modern data orchestration platform that simplifies running Apache Airflow. 
