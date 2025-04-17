1. 📌 Project Title & Badge:-
2. 
# IoT Sensor Data Analytics (Azure Data Engineering Project)
![Azure][azure-badge] ![Databricks][databricks-badge] ![Synapse][synapse-badge]


2. 📝 Project Description

An end-to-end data engineering pipeline using Azure services to process IoT-based environmental and energy sensor data. This project involves ingestion (ADF), transformation and anomaly detection (Databricks), and storage/analytics (Synapse).

3. 🧰 Tools & Technologies

- Azure Data Factory (ADF)
- Azure Databricks (PySpark)
- Azure Synapse Analytics (SQL Pool)
- Azure Blob Storage
- Power BI (Optional)
- Dataset: IoT Energy Consumption (from Kaggle)


4. 🚀 Key Features

- Real-world IoT dataset from buildings
- Null/duplicate detection, data validation in Databricks
- Anomaly detection using Z-Score method
- Seamless load to Synapse Analytics
- Queryable schema for reporting and dashboards

5. 🔄 Project Flow

1. Data uploaded to Azure Blob (Raw)
2. Ingestion with ADF → triggers Databricks
3. Data Cleaning, Enrichment & Anomaly Detection
4. Data stored in Synapse SQL Pool
5. Validated with SQL queries / dashboard-ready

6. 📂 Folder Structure
 
iot-energy-analytics/
├── notebooks/
│   └── databricks_cleaning
├── adf_pipeline/
│   └── ingest_blob_to_databricks
├── synapse_scripts/
│   └── create_table
│   └── validate_data
├── powerbi/
│   └── energy_dashboard
├── project_notes.md
└── README.md

7. 🧪 How to Run the Project
   
1. Clone the repository and upload dataset to Azure Blob
2. Import the ADF pipeline (`.json`)
3. Run Databricks notebook via ADF trigger
4. Verify data in Synapse using provided SQL scripts
5. (Optional) Connect Power BI for reporting


📊 Sample Queries

SELECT TOP 10 * FROM energy_sensor_data;
SELECT COUNT(*) FROM energy_sensor_data WHERE anomaly = 1;


✍️ Author & Contact


👨‍💻 Saikiran  










