## Project Overview
This project focuses on data cleaning, exploratory data analysis (EDA), and feature engineering for a real estate dataset. The dataset has been processed to handle missing values, outliers, and inconsistencies, followed by feature extraction and transformation for predictive modeling.

## Repository Structure

STAT5243 Project1/
│── README.md             # Project documentation  
│── data/                 # Raw and cleaned datasets  
│   ├── 5243data.csv  
│   ├── 5243_cleaned_data.csv  
│── 5243_CodeFile.ipynb            # Jupyter Notebooks  
│── Project1_report.pdf            # Final project report  
│── Project1_report.qmd            # Final project report in Quarto

## How to Run

1. Clone the Repository
git clone https://github.com/mingyan-xu/RealSTAT5243 Project.git
cd STAT5243 Project1

2. Run Python file
jupyter notebook notebooks/5243_CodeFile.ipynb

## Key Features
- Data Cleaning: Standardizes area and price units, handles missing values, and removes duplicates.  
- EDA: Analyzes property pricing trends, categorical distributions, and correlations.  
- Feature Engineering: Creates derived features and applies TF-IDF for text analysis.  
- Outlier Handling: Uses Z-score and IQR filtering to remove extreme values.  
