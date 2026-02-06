# DAY_28_PANDAS_ML
# 📅 Day 28 – Pandas Data Analysis (CSV, Filtering, iloc, Conditional Logic)

## 📌 Objective
On Day 28, I focused on **data manipulation using Pandas**.  
This includes loading CSV files, filtering data, applying conditional (if–else) logic, and accessing rows using `iloc`.

This marks my transition from **basic Python → data handling & analysis**.

---

## 🛠️ Tools & Libraries Used
- Python 3
- Pandas
- CSV file handling

---

## 📂 Dataset Used
**student_records_large.csv**

### Columns:
- Student_Name
- Department
- Year
- Section
- Marks
- Result
- Grade

---


df = pd.read_csv("student_records_large.csv")
print(df.head())
