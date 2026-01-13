📌 Project Overview

The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:

✅ Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

✅ Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

✅ Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

✅ Report and Presentation: Write a clear project report summarizing your key findings and business recommendations. Prepare a presentation that visually communicates insights and actionable recommendations to stakeholders.

Analyze e-commerce transactions to identify top products, customer loyalty trends, and revenue opportunities. Key outcomes include RFM segmentation, sentiment insights, and interactive visualizations for decision-makers. Built for scalable analytics pipelines.

Dataset

Source: Synthetic e-commerce data (purchases.csv, reviews.csv) with 10K+ records.
Features: Customer ID, purchase date, product category, quantity, revenue, review text, rating.
Size: ~5MB, mimicking real-world retail datasets like UCI Online Retail.

Tools & Technologies

Python: pandas, numpy, matplotlib, seaborn for EDA and cleaning.
SQL: PostgreSQL for queries on aggregated tables.
Visualization: Power BI for interactive dashboards.
Reporting: Gamma.app for PPT slides.
Environment: VS Code, Jupyter notebooks, pgAdmin.

Project Steps

Data Loading & EDA: Load CSVs into pandas; explore distributions, correlations, missing values.
Data Cleaning: Handle nulls, outliers, standardize formats; engineer features like order value.
Database Setup: Create PostgreSQL schema; load cleaned data via psycopg2.
SQL Analysis: Run queries for RFM metrics, top customers, trend analysis.
Power BI Dashboard: Connect to PostgreSQL; build visuals for sales, segments, forecasts.
Reporting: Export insights to Gamma PPT for executive summary.

Dashboard Highlights
Interactive Power BI report features:
Sales trends by category and time.
Customer segmentation (RFM matrix).
Top products heatmap.

Sentiment vs. revenue scatter plot.
<img width="910" height="489" alt="image" src="https://github.com/user-attachments/assets/dbff7064-1189-41d2-a4d1-3eadefcc7507" />
