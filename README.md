# Mental-Heakth_factor-Analysis 
Mini project analyzing mental health trends using Python, PostgreSQL, Excel, JSON, and Power BI. Collected, cleaned, and structured data, performed analysis, and created an interactive dashboard to visualize patterns and insights across factors affecting mental health.

# Overview
This mini-project explores mental health trends, focusing on how lifestyle factors, sleep, stress, and social interactions impact happiness and overall well-being. The main objective was to practice the end-to-end workflow of a Data Analyst, including data collection, cleaning, enrichment, and visualization, while applying Python, SQL, Excel, JSON, and Power BI in a real-world scenario.

# Technologies Used & Purpose
Technology Purpose Python (pandas, numpy) Load, explore, and preprocess raw CSV data. Check trends, inconsistencies, and structure the data for database storage. Excel Initial data cleaning and handling missing or inconsistent values. Useful for quick inspection and validation. postgreSQL Create new fields, transform data, and enrich datasets using SQL queries. Enables structured data ready for analysis. JSON Structure processed data for seamless integration with Power BI. Power BI Build an interactive dashboard visualizing trends, KPIs, and risk insights across gender, age, and lifestyle segments.

# Workflow
Data Acquisition & Exploration o Dataset fetched from Kaggle. 
Explored using Python to understand trends, distributions, and inconsistencies.

Data Cleaning & Preprocessing o Handled missing values, standardized column names, and verified data integrity in Excel.Ensured smooth transition to database storage.

Data Enrichment (PostgreSQL ) Several additional fields were created to facilitate analysis: Field Description / Logic Purpose age_group Categorized ages: Under 30, 30–45, 45+ Compare trends across age segments Has_condition Binary flag: 1 if “Mental Health Condition” exists, else 0 Easily aggregate prevalence of mental health conditions Sleep_Quality Good / Average / Poor based on Sleep Hours and Stress Level Assess relationship between sleep and stress Lifestyle_Segment Combination of Diet Type and Exercise Level Analyze lifestyle patterns holistically Lifestyle_Risk_Score Calculated from Sleep Quality, Stress Level, Activity Level Quantify lifestyle-related risk Condition_Severity Severity score (1–3) based on type of mental health condition Highlight high-risk conditions

Data Structuring (JSON) 
o Processed data exported to JSON for smooth input into Power BI. 
o Ensured consistent formatting for all visuals and KPIs.

Visualization (Power BI) 
o Created dashboard with KPIs, charts, scatter plots, heatmaps, and tables.
o Included slicers/filters for interactive exploration by gender, age, diet and few other factors. 
o Dashboard layout designed to quickly identify trends, risk segments, and correlations.

# Project Goal
The project demonstrates a complete data analytics workflow:

Raw data ingestion → Python exploration
Cleaning & preprocessing → Excel
Data enrichment → postgreSQL
Structuring for visualization → JSON
Insight generation → Power BI dashboard It allowed combining multiple tools and techniques while practicing logic creation, data transformation, and visualization design skills essential for a professional Data Analyst.
