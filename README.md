# 📌 Objective

This project tracks and analyzes farm-related expenses to provide insights on daily and weekly costs per field, categorized by crop, work type, and worker details.

# 🔹 Data Flow

## Source → Google Sheets / CSV file (Farm_Expenses_Backup_31052025.csv)

## Staging → SQL Server stage tables

## ETL → SQL scripts with CTEs, JOINs, MERGE statements for transformation

## Data Warehouse → Star schema with dimension & fact tables

## Visualization → Power BI reports for actionable insights

# 🗄 Data Model

## Dimensions:

dim_crop_details

dim_farm_field

dim_work_details

dim_worker_details

## Fact Table:

fact_farm_filed – contains expense records linked to all dimensions

# 📊 Power BI Insights
Reports Included:

## Trend Report → Tracks expense trends over time

## Weekly Report → Weekly cost breakdown by field & crop

# 💡 Key Insights
Most expensive crop and field

Seasonal trends in farming costs

Worker productivity vs expense

Work type cost breakdown

# ⚙️ Tech Stack
Data Source: Google Sheets / CSV

Database: SQL Server

ETL Tool: SQL Scripts

Visualization: Power BI

Version Control: GitHub

# 📂 Folder Structure
Farm_Expenses_Analytics/
│
├── 📂 Data
│   ├── Farm_Expenses_Backup_31052025.csv           # Raw source data
│   ├── Cleaned_Farm_Expenses.csv                   # Cleaned and transformed dataset
│
├── 📂 Scripts
│   ├── Excel_Data_Cleaning_Steps.xlsx               # Step-by-step transformation in Excel
│   ├── SQL_ETL_Procedures.sql                       # SQL Server scripts for transformation & load
│
├── 📂 DataModel
│   ├── DML.JPG                                      # Full data model
│   ├── dim_crop_details.JPG
│   ├── dim_farm_field.JPG
│   ├── dim_work_details.JPG
│   ├── dim_worker_details.JPG
│   ├── fact_farm_filed.JPG
│
├── 📂 PowerBI
│   ├── Farm_Expenses_Report.pbix                    # Power BI report file
│   ├── trend_report.JPG
│   ├── weekly_report.JPG
│
├── README.md                                        # Detailed project documentation
└── LICENSE
