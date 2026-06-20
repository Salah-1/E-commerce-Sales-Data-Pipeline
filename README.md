# FIFA-World-Cup-2026-Data-Pipeline

This pipeline automates the end-to-end flow of FIFA World Cup 2026 match data:
An ETL pipeline that extracts FIFA World Cup 2026 tournament data from CSV files, applies transformation logic with pandas, and loads the processed output to PostgreSQL (and eventually BigQuery) for downstream analytics — orchestrated with Apache Airflow.

## Overview

This pipeline automates the end-to-end flow of FIFA World Cup 2026 data:

- **Extract**: Pulls data from CSV files (teams, venues, matches, referees, squads, match events)
- **Transform**: Cleans, merges, and reshapes data using pandas
- **Load**: Writes the processed dataset to PostgreSQL (local) and BigQuery as analytics-ready tables

## Data Source (citation)

This project uses the [FIFA World Cup 2026 Dataset](https://github.com/mominullptr/FIFA-World-Cup-2026-Dataset) by MD Mominul Islam, sourced from Kaggle.

```
@dataset{fifa_world_cup_2026,
  author = {MD Mominul Islam},
  title = {FIFA World Cup 2026 Dataset},
  year = {2026},
  publisher = {Kaggle}
}
```

## Tech Stack

- **Python** – core scripting and transformation logic
- **Pandas** – data manipulation and cleaning
- **PostgreSQL** – local staging / data warehouse
- **Apache Airflow** – pipeline orchestration and scheduling
- **Google BigQuery** – cloud data warehouse / output destination (future -may be replaced by Power BI)
