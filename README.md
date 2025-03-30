# Tokyo 2021 Olympic Data Analytics Pipeline

This project demonstrates the development of an end-to-end ETL (Extract, Transform, Load) pipeline using **Microsoft Azure** cloud services and **Tableau Public** to analyze the **Tokyo 2021 Olympic Games** dataset.

## Project Overview

This pipeline automates the flow of raw Olympic data from a GitHub repository to interactive dashboards. The process includes:
- Data ingestion using **Azure Data Factory (ADF)**
- Storage in **Azure Data Lake Gen2**
- Data transformation with **Azure Databricks** using PySpark
- SQL-based analysis via **Azure Synapse Analytics**
- Dashboard visualization using **Tableau Public**

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Azure Data Factory | Automated data ingestion from GitHub |
| Azure Data Lake Gen2 | Storage for raw and transformed data |
| Azure Databricks | Data transformation using PySpark |
| Azure Synapse Analytics | SQL-based querying and analysis |
| Tableau Public | Visualizing Olympic insights interactively |

---

##  Dataset

The dataset includes multiple CSV files:
- `athletes.csv`
- `medals.csv`
- `entriesgender.csv`
- `teams.csv`
- `coaches.csv`

These files contain information on athlete demographics, medal counts, event participation, team composition, and gender statistics.

---

## Key Dashboards

- **Medal Distribution by Country**
- **Athlete Participation by Gender and Discipline**
- **Most Popular Sports**
- **Top Performing Countries**
- **Team & Coach Distribution**

Sample dashboard hosted on [Tableau Public](#) *(insert your link once published)*

---

## Project Structure

```bash
tokyo-olympic-etl
 ┣  raw-data
 ┣  transformed-data
 ┣  notebooks
 ┃ ┗  data_transformation.py
 ┣ 📁 synapse-scripts
 ┃ ┗  analysis_queries.sql
 ┣ 📁 tableau
 ┃ ┗  dashboard.twb
 ┗  README.md
