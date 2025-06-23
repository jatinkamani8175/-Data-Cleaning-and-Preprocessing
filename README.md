# Data Cleaning — Supplement Sales Data

## 📁 Dataset Used
**File:** `Supplement_Sales_Weekly_Expanded.csv`  
**Description:** Contains weekly sales data for health supplements including product details, price, revenue, and returns across various platforms and locations.

---

## 🎯 Objective
To clean and preprocess the dataset by handling:
- Missing values
- Duplicate records
- Inconsistent text formatting
- Date formatting
- Incorrect column names and data types

---

## 🔧 Cleaning Steps

1. **Loaded** the dataset using Pandas.
2. **Removed duplicate rows** using `.drop_duplicates()`.
3. **Standardized text fields** like product name, category, platform, and location (e.g., `.str.title()`).
4. **Converted the date** column to proper datetime format using `pd.to_datetime()`.
5. **Renamed columns** to lowercase and snake_case for consistency.
6. **Converted numeric fields** like price, revenue, and units sold to proper data types.
7. **Dropped rows with missing values** to ensure data quality.

---

## ✅ Output
The cleaned dataset is saved as:

**`cleaned_sales_data.csv`**

---

## 🛠 Tools Used
- Python 3
- Pandas Library

---

## 👨‍💻 Author
Data Analyst Internship Task  
Task Name: `Data Cleaning and Preprocessing`
