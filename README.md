# Cleaned-Raw-data-using-Pandas-and-Numpy
The Student Data Cleaning Project focuses on transforming raw, unstructured student data into a clean, reliable, and structured format using Python, NumPy, and Pandas.



## 📌 Overview
This project demonstrates how to clean and preprocess a **student dataset** using **NumPy** and **Pandas** inside a Jupyter Notebook.  
The notebook `studnet_uncleaned_data.ipynb` shows step-by-step data cleaning operations to transform raw student data into a structured, ready-to-use format.  

Data cleaning is one of the most crucial steps in the **data science workflow**. By removing inconsistencies, handling missing values, and standardizing formats, we ensure that the dataset is reliable for **analysis, visualization, and machine learning**.

---

## ⚙️ Tools & Libraries
- **Python 3.x**
- **Jupyter Notebook**
- **NumPy** → for numerical operations
- **Pandas** → for data manipulation and cleaning

---

## 📂 Files
- **studnet_uncleaned_data.ipynb** → Notebook containing raw data exploration and cleaning steps.
- **data/**
  - `raw/` → Contains the original uncleaned dataset.
  - `processed/` → Contains the cleaned and processed dataset.

---

## 🧹 Data Cleaning Steps
The following operations were applied to clean the dataset:

1. ## Handling Missing Values**
   - Identified missing/NaN values.
   - Filled missing entries using mean, median, or mode depending on the column type.
   - Dropped unnecessary rows/columns with excessive missing values.

2. ## Data Inspection**
   - Used `df.info()` to display column names, data types, and memory usage.
   - Used `df.describe()` to generate summary statistics like mean, median, min, max, and quartiles.

3. ## Data Type Conversion**
   - Converted string/object columns into correct numeric or datetime formats.
   - Ensured consistency across categorical and numeric fields.

4. ## Other Cleaning Tasks**
   - Removed duplicate rows (if any).
   - Standardized column names for readability.
   - Checked and fixed inconsistencies (e.g., spelling mistakes, mixed data formats).
   - Reorganized columns for better structure.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/student-data-cleaning.git
   cd student-data-cleaning
