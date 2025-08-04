# 📁 Task 1: Data Cleaning and Preprocessing — Netflix Dataset

## 🎯 Objective
Clean and preprocess the **Netflix Movies and TV Shows dataset** using Python and Pandas, identifying key data quality issues such as missing values, duplicates, inconsistent formatting, and incorrect data types.

---

## 🛠️ Tools Used
- Python 3.8+
- Pandas
- Matplotlib (for visualization)
- Jupyter Notebook / Google Colab

---

## 🧹 Data Cleaning Steps Performed
- Handled missing values using `dropna()` and `fillna()`
- Removed duplicate records using `drop_duplicates()`
- Standardized string entries in text columns (e.g. country, type)
- Converted date fields using `pd.to_datetime()`
- Renamed column headers for consistency (lowercase, no spaces)
- Verified and corrected data types (e.g. release_year as integer)
- Created new columns: `year_added`, `month_added`, `year_month`

---

## 📊 Visualization
The number of movies and TV shows added over time was visualized using a bar chart, allowing clearer comparisons across months.

📎 image 2.png — Visual summary of Top 10 Countries with Most Content on Netflix.

---

## 📁 Files Included
- `netflix_cleaned.csv`: Final cleaned dataset
- `task1_cleaning.ipynb`: Full notebook with data cleaning steps
- `content_over_time.png`: Visualization showing content trends
- `README.md`: Documentation summary

---

## 📅 Submission Notes
This repository was created for **Day 1 of the Data Analyst Internship**. All task files are organized in the folder `Task_1_Data_Cleaning/` and submitted before the deadline (10:00 PM).

---

## 📬 Contact
For any follow-up or clarification, feel free to reach out via LinkedIn or email.

