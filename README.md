📊 Project Overview

This project analyzes a simulated CRM (Customer Relationship Management) dataset to uncover insights into sales team performance, agent effectiveness, quarterly sales trends, and product win rates.

The goal is to demonstrate end-to-end data analysis skills, from raw data ingestion and SQL-based data modeling to final business insights and visualizations.

🗂️ Datasets

The project uses four core datasets:

Dataset	Description

accounts.csv	Contains information about client accounts.

products.csv	List of products being sold, including categories and pricing.

sales_pipeline.csv	Tracks individual sales opportunities, their status, value, and related sales agent.

sales_teams.csv	Details of sales teams and the agents assigned to them.


🔍 Key Business Questions

The analysis answers the following:

How is each sales team performing compared to the rest?

Are any sales agents lagging behind?

Are there any quarter-over-quarter trends?

Do any products have better win rates?

📓 Notebooks
Notebook	Description
01_create_sql_tables.ipynb	Uploads .csv files into SQL tables using SQLite. Sets up the database schema for analysis.
02_crm_sales_analysis.ipynb	Performs analysis using SQL queries and visualizations. Contains the final queries used to derive insights.

These notebooks are meant to be run in order, with the first one setting up the database and the second one doing the heavy analysis.

🧰 How to Use

Clone this repository:

git clone https://github.com/yourusername/crm-sales-opportunities.git
cd crm-sales-opportunities


Install dependencies:

pip install -r requirements.txt


Run the notebooks in order:

notebooks/01_create_sql_tables.ipynb

notebooks/02_crm_sales_analysis.ipynb

📁 Project Structure
crm-sales-opportunities/
│
├── data/
│   ├── accounts.csv
│   ├── products.csv
│   ├── sales_pipeline.csv
│   └── sales_teams.csv
│
├── notebooks/
│   ├── 01_create_sql_tables.ipynb
│   └── 02_crm_sales_analysis.ipynb
│
├── README.md

📌 Key Skills Demonstrated

Exploratory Data Analysis (EDA)

Business Insight Generation

Sales Funnel & Pipeline Metrics

Team & Product Performance Benchmarking

🚀 Future Improvements

Add an interactive dashboard (e.g., Power BI, Tableau, or Plotly Dash)

Include predictive modeling (e.g., close probability prediction)

Automate data refresh and reporting with scripts or scheduled pipelines
