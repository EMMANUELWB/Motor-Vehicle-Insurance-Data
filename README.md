
# 🚗 Motor Vehicle Insurance Data Analysis

## 📌 Project Overview

This project explores a motor vehicle insurance dataset, focusing on **data cleaning, quality checks, exploratory data analysis (EDA), and visualizations**.
The goal is to assess the dataset’s consistency, uncover patterns in claims, and highlight key insights for insurance risk and policy analysis.

All analysis was performed using **Excel** (for profiling, cleaning, and EDA) and **Tableau** (for dashboards).

---

## 📂 Repository Structure

```
Motor-Vehicle-Insurance-Data/
├── data/
│   ├── raw/
│   │   └── Motor_vehicle_insurance_data.csv       # Original raw dataset
│   └── clean/
│       └── Motor_vehicle_insurance_data_AL.xlsx  # Exported clean worksheet only
├── analysis/
│   └── Motor_vehicle_insurance_data_ALL.xlsx     # Working workbook: clean worksheet + EDA + logs
├── visualizations/                                # Tableau dashboards or screenshots
├── docs/                                         # Data dictionary, methodology notes
└── README.md
```

---

## 🧹 Data Cleaning & Profiling Methodology

### 1. **Data Profiling**

* Inspect the dataset structure (columns, first few rows).
* Confirm data types (dates, numbers, text).
* Generate summary statistics for numerical and categorical columns.
* Identify missing values and assess the impact on analysis.

### 2. **Data Cleaning**

* Handle missing values with deletion or imputation (mean/median/mode).
* Correct data types where necessary (e.g., convert strings to dates).
* Detect and remove duplicate rows.

### 3. **Data Validation**

* Detect outliers using IQR or Z-score methods.
* Check logical consistency (e.g., policy start date ≤ end date, realistic vehicle ages).

### 4. **Data Documentation**

* Create a **data dictionary** describing each column, its type, meaning, and transformations applied.

### 5. **Data Auditing**

* Review all steps to ensure the dataset is clean, consistent, and ready for analysis.

> **Note:** All profiling, cleaning, and validation steps are recorded inside `Motor_vehicle_insurance_data_ALL.xlsx` for reproducibility.

---

## 🔍 Exploratory Data Analysis (EDA)

* **Discrete variables:** Frequency distributions and observations are in `Discrete_Numerical_Column`.
* **Continuous variables:** Histograms, log transformations, and handling strategies are in `EDA_CONT_Numerical_Column`.

All EDA steps are documented inside the working Excel file in `analysis/`.

---

## 📊 Visualizations & Findings

* Dashboards built in Tableau visualize:

  * Distribution of insurance claims by demographics.
  * Frequency and cost of claims.
  * Policy type and vehicle usage patterns.

Tableau dashboards (or screenshots) can be found in the `visualizations/` folder.

---

## 🚀 Next Steps

* Expand analysis with predictive modeling (e.g., claim likelihood).
* Automate cleaning and EDA pipeline using **SQL or R**.
* Scale Tableau dashboards for live reporting.

---

## 👤 Author

**Emmanuel Agbo** — Data Analyst | Excel • SQL • Tableau • R

---

