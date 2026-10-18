# NEXT_GEN-DSC-INTERNSHIP
A 1-month data science internship
# 📊 Applicant Dataset - Data Cleaning & Exploration (Week 1)

## Project Overview
- This project focuses on cleaning, wrangling, and performing initial data exploration on raw applicant records
- The goal is to transform a messy real-world dataset into a reliable, standardized format suitable for downstream analytics

All data processing is fully automated in Python using `pandas` to ensure 100% reproducibility without manual spreadsheet edits


## 📂 Repository Structure

- Week1_Data_Cleaning_[YourName].ipynb   # Main Jupyter/Colab notebook with code & explanations
-  applicants.csv                         # Raw, uncleaned dataset
-  applicants_cleaned.csv                 # Final processed dataset
-  README.md                              # Project documentation

## 1. Exploratory Data Analysis (EDA):
- Assessed the data shape, data types 
- Identified missing values and duplicate values
## 2. Handled missing values:
- Dropped rows missing Applicant Name (critical identifier).
- Filled missing University values with 'Not Specified' and missing Status with 'Under Review'
## 3. Removed dupicates:
- Removed exact row duplicates and near-duplicates identified by matching Email addresses.
## 4. Data formatting and standardisation
- Stripped extra whitespace and standardized casing across all text fields.
- Mapped inconsistent domain variations (e.g., "web dev", "WEB DEV") into unique categories.
