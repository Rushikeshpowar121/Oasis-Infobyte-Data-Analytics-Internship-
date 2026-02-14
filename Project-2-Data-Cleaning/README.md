
# Project 2 — Data Cleaning (NYC Airbnb Dataset)

## 📊 Objective
Clean and preprocess the Airbnb dataset by handling missing values, correcting data types, and preparing the dataset for analysis.

## 📁 Dataset
New York City Airbnb Open Data

Columns include:
- id
- name
- host_name
- neighbourhood_group
- room_type
- price
- minimum_nights
- number_of_reviews
- last_review
- reviews_per_month
- availability_365

## 🧹 Data Cleaning Steps
1. Checked missing values
2. Filled missing names using forward fill
3. Filled missing reviews_per_month with median
4. Converted last_review to datetime
5. Verified data types
6. Removed duplicates
7. Checked outliers in price column
8. Saved cleaned dataset

## 🛠 Tools Used
- Python
- Pandas
- Jupyter Notebook

## 📌 Files in this Folder
- `Airbnb_Data_Cleaning.ipynb` → Cleaning process
- `AB_NYC_2019.csv` → Raw dataset
- `cleaned_airbnb.csv` → Cleaned dataset
- `README.md`

## 🎯 Outcome
Produced a clean dataset ready for analysis and modeling.

