# Tokyo Olympics Data Analysis

This project demonstrates the usage of PySpark for analyzing Tokyo Olympics data stored in Azure Data Lake. 
The workflow includes mounting an Azure Data Lake storage, loading data, and performing data transformation and analysis.

---

## Prerequisites

- **Azure Account**: An Azure Data Lake storage account is required.
- **Databricks Workspace**: A Databricks environment is used for PySpark operations.
- **PySpark**: Knowledge of PySpark and its modules (`pyspark.sql.functions`, `pyspark.sql.types`).

---

## Data Sources

The project uses the following datasets stored in Azure Data Lake:

1. **athletes.csv**: Details of athletes.
2. **coaches.csv**: Details of coaches.
3. **entriesgender.csv**: Gender-wise entries for each discipline.
4. **medals.csv**: Medal count by country.
5. **teams.csv**: Team-wise details.

---


## Results

- **Top Gold Medal Winners**: United States, People's Republic of China, and Japan.
- **Average Gender Participation**: Gender-wise participation ratio for each discipline.

---

## Environment Details

- **Spark Version**: 3.3.2
- **Cluster Mode**: `local[*]`
- **Tools**: Azure Databricks, PySpark

---

## How to Run

1. Mount the Azure Data Lake storage.
2. Load datasets into PySpark DataFrames.
3. Perform data exploration and transformation.
4. Execute analysis scripts to extract insights.

---

## Authors

This project was developed as a demonstration of PySpark's capabilities for data analysis.
