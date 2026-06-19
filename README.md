# FIFA-World-Cup-2026-Data-Pipeline
 
This pipeline automates the end-to-end flow of FIFA World Cup 2026 match data:
An ETL pipeline that extracts tournament data from a SQL database and CSV files, applies transformation logic with pandas, and loads the processed output to BigQuery for downstream analytics — orchestrated with Apache Airflow.
 
## Overview
This pipeline automates the end-to-end flow of FIFA World Cup 2026 data:
 
* **Extract**: Pulls data from a SQL database and CSV files (teams, venues, matches, referees, squads, match events)
* **Transform**: Cleans, merges, and reshapes data using pandas
* **Load**: Writes the processed dataset to BigQuery as analytics-ready tables
## Tech Stack
 
* **Python** – core scripting and transformation logic
* **Pandas** – data manipulation and cleaning
* **SQL** – source data extraction
* **Apache Airflow** – pipeline orchestration and scheduling
* **Google BigQuery** – data warehouse / output destination
