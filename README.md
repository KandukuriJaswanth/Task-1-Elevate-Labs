# Task-1-Elevate-Labs
# 🧼 Customer Personality Analysis – Data Cleaning Project

This project performs complete data cleaning and preprocessing on a real-world customer dataset using Python and Pandas. It includes missing value handling, duplicate removal, outlier treatment, and report generation.

## 📁 Dataset
- Name: `Customer_Personality_Analysis_90k.csv`
- Size: ~90,000 records
- Format: CSV

## ✅ Key Features
- Cleaned and standardized column names
- Removed duplicate records
- Handled missing values using median imputation
- Standardized text data (e.g., gender, marital status)
- Fixed incorrect data types (e.g., age, income)
- Detected and clipped outliers using the IQR method
- Generated Excel summary report
- Exported cleaned dataset as CSV

## 🛠 Technologies
- Python 3
- Pandas
- ExcelWriter (for report generation)

## 📦 Outputs
- `Cleaned_Customer_Data.csv`
- `Data_Cleaning_Report.xlsx`

## 📌 Usage
```bash
python clean_customer_data.py
