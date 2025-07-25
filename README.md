# Uber Fares Dataset Analysis

## Course Information  
- Course: Introduction to Big Data Analytics (INSY 8413)  
- Instructor: Eric Maniraguha ([eric.maniraguha@auca.ac.rw](mailto:eric.maniraguha@auca.ac.rw))  
- Assignment: Uber Fares Dataset Analysis using Power BI  
- Assignment Date: July 20–25, 2025  

## Project Overview  
This project analyzes the Uber Fares Dataset sourced from Kaggle to gain insights into fare patterns, ride durations, and operational metrics. Python is used for data cleaning, exploratory data analysis (EDA), and feature engineering, while Power BI creates an interactive dashboard to visualize key findings.

## Folder Structure  
- /data — Zipped cleaned Uber fares dataset (.zip) ready for Power BI import  
- /powerbi — Power BI Desktop report file (.pbix) with interactive dashboards  
- /report— Jupyter notebooks covering data loading, cleaning, EDA, feature engineering, and embedded visualizations  

## Methodology  
1. Data Understanding and Preparation  
   - Loaded raw data into Pandas DataFrames.  
   - Assessed dataset structure, variable types, and initial data quality.  
   - Cleaned data by handling missing values and correcting inconsistencies.  
   - Exported cleaned data for use in Power BI.  

2. Exploratory Data Analysis (EDA)  
   - Generated descriptive statistics (mean, median, mode, quartiles).  
   - Identified outliers and distribution patterns.  
   - Examined correlations between fare amount, distance, and time variables.  

3. Feature Engineering  
   - Extracted temporal features (hour, day, month, day of week).  
   - Created peak vs. off-peak time indicators.  
   - Encoded categorical variables appropriately.  

4. Power BI Dashboard Development  
   - Imported, cleaned, and enhanced data.  
   - Created visualizations for fare distribution, ride durations, and temporal trends.  
   - Developed an interactive dashboard with filters and drill-down features.  

## Summary of Findings  
- Fare amounts generally increase with distance traveled, with some exceptions due to surge pricing.  
- Peak hours correspond to higher ride volumes and fare amounts.  
- Seasonal and weekday variations affect ride demand and pricing patterns.  
- Identified key periods for operational focus based on ride density and fare trends.  

## How to Use This Repository  
1. Download and unzip the dataset from the /data folder.  
2. Open the Power BI report file in /powerbito explore interactive visualizations.  
3. Review or run the Jupyter notebooks in /report for detailed analysis and methodology.  

## Tools & Technologies  
- Python 3.x (Pandas, NumPy, Matplotlib, Seaborn)  
- Power BI Desktop   
- Jupyter Notebook  

## Contact  
For questions or further information, please contact: email: pacific.uwitonze112@gmail.com or GitHub: uwitonze8]  
