# Data Analytics Project

## Overview
This project analyzes retail purchase transctions by customers from different cities and states in the US covering the four seasons (winter, summer, Fall, and Spring) to uncover insights on the factors driving purchases such as the revenue contributions by age groups, subscription patterns, loyalty, shipping, and impact of discounts. The workflow covers the full analytics pipeline — from raw data ingestion to a polished, interactive dashboard and a written project report.

## 🎯 Objectives
- Clean and prepare raw data for analysis
- Explore key trends, patterns, and outliers in the dataset
- Query and validate data using SQL (PostgreSQL)
- Visualize findings through an interactive Power BI dashboard
- Summarize insights and recommendations in a project report

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy, Matplotlib/Seaborn) | Data loading, cleaning, and exploratory data analysis (EDA) |
| PostgreSQL | Data storage, querying, and validation |
| Power BI | Interactive dashboard and data visualization |
| Jupyter Notebook | Analysis documentation and reproducibility |

## 📁 Project Structure
```
├── data/
│   ├── raw/                # Original, unprocessed dataset
│   └── cleaned/            # Cleaned dataset ready for analysis
├── notebooks/
│   └── eda_and_cleaning.ipynb   # Data loading, cleaning, and EDA
├── sql/
│   └── queries.sql         # PostgreSQL queries used for analysis
├── dashboard/
│   └── dashboard.pbix      # Power BI dashboard file
├── report/
│   └── project_report.pdf  # Final written report with insights
└── README.md
```

## 🔍 Project Workflow

### 1. Data Loading
The dataset was imported into Python using Pandas for initial inspection and preparation.

### 2. Data Cleaning
Handled missing values, duplicates, inconsistent formatting, and data type corrections to ensure analysis-ready data.

### 3. Exploratory Data Analysis (EDA)
Explored distributions, trends, and relationships between variables using visualizations and summary statistics to guide further analysis.

### 4. SQL Analysis (PostgreSQL)
Loaded the cleaned data into PostgreSQL and ran queries to extract aggregated metrics, validate findings from EDA, and answer specific business questions.

### 5. Power BI Dashboard
Built an interactive dashboard to visualize key metrics and trends, enabling stakeholders to explore the data dynamically.

### 6. Project Report
Compiled a summary report outlining methodology, key findings, and actionable recommendations based on the analysis.

## 📈 Key Insights
- 
- 
-

## 📌 Dashboard Preview
<img width="1115" height="622" alt="interactive dashboard" src="https://github.com/user-attachments/assets/109c2179-ca2e-4f9f-ad2a-1cef5aac3204" />


## 🚀 How to Run This Project
1. Clone this repository
2. Install required Python packages: `pip install -r requirements.txt`
3. Run `notebooks/eda_and_cleaning.ipynb` to reproduce data cleaning and EDA
4. Load the cleaned dataset into PostgreSQL and execute `sql/queries.sql`
5. Open `dashboard/dashboard.pbix` in Power BI to explore the dashboard

## 📄 Deliverables
- Cleaned dataset
- EDA notebook
- SQL query file
- Power BI dashboard
- Final project report (PDF)

## 👤 Author
**Brian Among'a **

