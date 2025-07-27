Uber Fares Dataset Analysis using Power BI
Project Overview
This project involves a comprehensive analysis of the Uber Fares Dataset to gain insights into fare patterns, ride durations, and key operational metrics. The analysis is performed using Python for data preparation and exploratory data analysis (EDA), and Power BI for interactive dashboard creation and visualization. The objective is to develop a robust data analysis workflow and present findings through an interactive dashboard and detailed documentation.

Dataset
The dataset used for this analysis is the Uber Fares Dataset, sourced from Kaggle. It contains information related to Uber rides, including fare amounts, trip distances, timestamps, and other relevant attributes.

Project Structure
This repository is organized to provide a clear overview of the project's components and workflow.

.
├── data/
│   ├── raw/
│   │   └── uber_fares_dataset.csv  # Original downloaded dataset
│   └── processed/
│       ├── cleaned_uber_fares.csv  # Cleaned dataset after handling missing values
│       └── enhanced_uber_fares.csv # Dataset with new features for Power BI
├── notebooks/
│   └── uber_fares_eda.ipynb      # Jupyter notebook for data understanding, cleaning, and feature engineering
├── powerbi/
│   └── Uber_Fares_Dashboard.pbix # Power BI Desktop file containing the interactive dashboard
├── documentation/
│   ├── data_loading_screenshots/   # Screenshots of data loading process
│   ├── data_cleaning_screenshots/  # Screenshots of data cleaning steps
│   ├── dax_formulas_screenshots/   # Screenshots of DAX formulas used (if any)
│   └── dashboard_development_screenshots/ # Screenshots of dashboard development stages
├── reports/
│   └── final_report.md             # Comprehensive analytical report (Markdown format)
└── README.md                       # This README file

Directory Breakdown:
data/: Contains both the raw and processed versions of the dataset.

raw/: Stores the original, untouched dataset as downloaded.

processed/: Stores the cleaned dataset ready for Power BI, and the enhanced dataset with engineered features.

notebooks/: Houses the Jupyter notebook used for Python-based data preparation, EDA, and feature engineering.

powerbi/: Contains the Power BI Desktop file (.pbix) which is the core of the interactive dashboard.

documentation/: A collection of subdirectories holding screenshots that document various stages of the project, from data loading to dashboard development.

reports/: Contains the final analytical report, detailing the findings and recommendations.

README.md: This file, providing an overview of the project.
