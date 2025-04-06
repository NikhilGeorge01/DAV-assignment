

# 📊 Sales Data Analysis Project

This project performs a complete exploratory data analysis (EDA) on a sample sales dataset. It includes data cleaning, statistical operations, pivot tables, and insightful visualizations using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## 📁 Files Included

- `sales_data_sample.csv` — Raw sales dataset (from Kaggle)
- `Sales_Data_Analysis.ipynb` — Jupyter Notebook with code and comments
- `Sales_Data_Analysis_Report.pdf` — Summary report of findings and visual insights

## 🧰 Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

## 📌 Features

### ✅ Data Loading & Cleaning
- Handled missing values
- Converted date columns to datetime
- Transformed categorical columns

### ✅ Exploratory Data Analysis
- Basic stats: mean, median, std, etc.
- Grouped analysis using `groupby()`
- Pivot tables with multiple aggregation strategies

### ✅ Visualizations
- Histogram of Sales
- Barplot of Deal Size vs Total Sales
- Scatterplot of Quantity vs Price (colored by Deal Size)
- Boxplot of Sales across Quarters

### ✅ Bonus Operations
- Added new derived columns (e.g., `Profit`)
- Normalized numerical columns using z-score
- Filtered and segmented data for deeper insight

## 📈 Key Findings
- Mid-size deals dominate in total sales.
- Larger quantities tend to have lower prices per unit (bulk effect).
- Seasonal patterns visible in quarterly sales.
- Some product lines outperform others significantly.

## 🔍 Dataset Source
This dataset was sourced from Kaggle: [Sales Data Sample](https://www.kaggle.com/datasets)

## 💡 How to Run
1. Clone the repository
2. Open `Sales_Data_Analysis.ipynb` in Jupyter Notebook or any compatible environment
3. Run all cells step-by-step


