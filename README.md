# 📊 Data Cleaning and Dashboard Project

![Dashboard Preview](Bike_Buyers.Excel/Dashboard.png)

## 📝 Overview

This project focuses on cleaning a dataset and visualizing insights through an interactive dashboard. It includes the raw and cleaned datasets, Python scripts for preprocessing, and a dashboard to explore the data effectively.

---

## 📂 Dataset Description

### 🔹 Raw Data
- **Description**: Contains unprocessed data with potential quality issues.  
- **Common Issues**:
  - Missing values in columns like `Age`, `Salary`
  - Inconsistent formats in the `Date` column
  - Duplicate entries
  - Outliers in `Salary` and other numeric fields

### 🔹 Cleaned Data

- **Description**: Processed version with quality issues resolved.

**Cleaning Steps**:
- Imputed missing values using mean/median/mode
- Standardized date formats to `YYYY-MM-DD`
- Removed duplicate entries
- Handled outliers through capping, removal, or transformation

## 📈 Dashboard

### 🔍 Features:
- **Interactive Filters** (e.g., by category or date range)
- **Visualizations**: Bar charts, line graphs, histograms
- **Key Metrics**: Average salary, total records, etc.
