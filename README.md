# Task-1-VirtualWorks
Data Cleaning and Structural Validation - VirtualWork Internship
Task 1 - Data Cleaning & Structural Validation

Internship: VirtualWork (Data Analysis / Data Science Track)
Intern: Sureka Mathivanan

Objective

Transform raw, unstructured data into a reliable format for analysis. The dataset contains duplicate entries, missing values, and inconsistent formats. This project designs a cleaning process that ensures accuracy while preserving data integrity.

Steps Performed


Data Loading – Imported the raw CSV dataset
Initial Exploration – Checked data types, structure, and missing values
Duplicate Removal – Identified and dropped duplicate rows
Missing Value Handling – Filled missing Age and Purchase Amount with median values; filled missing Name/Phone with placeholders
Text Standardization – Fixed inconsistent casing across Name, Gender, Country, and Category columns
Date Format Correction – Unified mixed date formats (YYYY-MM-DD and YYYY/MM/DD) into a single standard format
Email Validation – Checked and corrected invalid email entries
Data Export – Saved the final cleaned dataset as cleaned_data.csv
Visualization – Created charts to summarize missing data, category distribution, and purchase amount distribution


Tools Used


Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook


Outcome

The raw dataset, originally containing duplicate rows, missing fields, and inconsistent formatting, was cleaned and validated. The final dataset is structurally consistent and ready for further analysis or visualization tasks.

Reference

Task video reference: VirtualWork Task 1
