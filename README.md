# 📌 Objective

This project tracks and analyzes farm-related expenses to provide insights on daily and weekly costs per field, categorized by crop, work type, and worker details.

# 🔹 Data Flow

## Source → Google Sheets / CSV file (Farm_Expenses_Backup_31052025.csv)

## Staging → SQL Server stage tables

## ETL → SQL scripts with CTEs, JOINs, MERGE statements for transformation

## Data Warehouse → Star schema with dimension & fact tables

## Visualization → Power BI reports for actionable insights

# 🗄 Data Model
![DML](dwh/dml.jpg)

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
## Data Source: Google Sheets / CSV

## Database: SQL Server

## ETL Tool: SQL Scripts, SSIS

## Visualization: Power BI

## Version Control: GitHub
