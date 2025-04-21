# Task-1-Data-Cleaning-and-Preprocessing
🧹 Cleaned and processed a food preference survey dataset using Python (Pandas). Tasks included handling missing values, removing duplicates, standardizing column formats, and correcting data types. Final dataset is analysis-ready.

# 🧹 Dataset Cleaning Project – Food Preferences Dataset

## 📌 Objective
This project focuses on cleaning and preparing a raw dataset containing survey data on food preferences. The dataset includes a variety of numerical, categorical, and open-ended responses. The goal is to make the data analysis-ready by handling missing values, standardizing formats, and correcting data types.

---

## 🛠 Tools Used
- **Python 3**
- **Pandas**
- **Google Colab** (for execution)
- **CSV Files** (Raw input & cleaned output)

---

## 📁 Files Included
- `food_coded.csv` – Original raw dataset
- `food_coded_cleaned.csv` – Cleaned and processed dataset
- `codebook_food.docx` – Data dictionary/codebook for interpretation
- `data_cleaning.ipynb` – Python notebook with all steps
- `README.md` – This file

---

## 🔄 Cleaning Steps Performed

1. **Missing Values**  
   - Dropped columns with more than 50% missing data  
   - Filled remaining nulls using median (for numeric) and mode (for categorical)

2. **Duplicates**  
   - Removed duplicate rows using `drop_duplicates()`

3. **Standardizing Categorical Values**  
   - Example: `Gender` column mapped from numeric (1/2) to text (`Female`, `Male`)

4. **Column Renaming**  
   - Converted column names to lowercase and replaced spaces with underscores for consistency

5. **Data Type Correction**  
   - Converted `GPA` and `weight` columns to numeric types

6. **Saved Cleaned Data**  
   - Exported final cleaned dataset as `food_coded_cleaned.csv`

---

## ✅ Final Output
The cleaned dataset is now:
- Free of missing data and duplicates  
- Properly formatted and standardized  
- Ready for further analysis, visualization, or modeling

---
