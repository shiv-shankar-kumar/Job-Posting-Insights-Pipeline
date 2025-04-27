# 💼 Job Postings Insights Pipeline

An end-to-end data pipeline built on Azure to ingest, clean, analyze, and visualize job posting trends using ADF, Databricks, NLP, Delta Lake, and Power BI.

---

## 🚀 Technologies Used

- **Azure Data Factory** – for orchestrating pipelines and ingesting data from Blob Storage
- **Azure Databricks** – for scalable data processing using PySpark
- **Python & SQL** – for cleaning, NLP, and rule-based transformations
- **Delta Lake** – for versioned and incremental data storage (Bronze → Silver → Gold)
- **Power BI** – for dashboarding skill trends and hiring patterns

---

## 📊 Key Features

- Automated ingestion using **ADF triggers & parameterized datasets**
- Applied **NLP techniques** for extracting keywords and classifying job roles
- Built **modular Databricks notebooks** for scalable data transformation
- Final insights visualized in **Power BI dashboards**

---

## 📁 Project Structure

```bash
├── data_ingestion/
├── data_processing/
├── data_storage/
├── analytics/
├── utils/
├── config/
├── README.md
└── requirements.txt
