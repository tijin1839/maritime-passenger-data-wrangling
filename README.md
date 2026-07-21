# maritime-passenger-data-wrangling


An exploratory data analysis and data hygiene pipeline featuring rigorous missing value imputation, anomaly auditing, and custom feature engineering.

## Project Overview
This repository contains a structured Jupyter Notebook demonstrating an end-to-end data analysis workflow. The objective is to audit raw datasets, ensure data integrity through systematic data hygiene, and extract meaningful insights using robust visualization tools.

## Key Pipeline Steps
1. **Business Understanding & Objectives:** Outlining the core analytical goals.
2. **Data Loading & Initial Inspection:** Assessing data types, shapes, and structural integrity.
3. **Data Hygiene & Anomaly Audits:** Detecting duplicates, formatting inconsistencies, and anomalies.
4. **Missing Value Imputation Strategy:** Applying logical, domain-driven handling of null values.
5. **Feature Engineering:** Creating high-value derived features (e.g., family size, title extraction).
6. **Exploratory Data Analysis (EDA):** Generating clean charts and statistical summaries to uncover trends.
7. **Summary of Insights:** Consolidating actionable takeaways.

## Repository Structure
```text
passenger-manifest-eda/
├── analysis.ipynb          # Main Jupyter notebook containing the complete EDA & cleaning pipeline
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
└── .gitignore              # Exclude checkpoints, virtual environments, and system junk
