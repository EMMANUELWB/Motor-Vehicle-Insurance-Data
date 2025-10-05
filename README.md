# 🚗 Motor Vehicle Insurance Data Analysis

## 📌 Project Overview

This project investigates a motor vehicle insurance portfolio with a strict focus on **data quality, reproducible cleaning, exploratory data analysis (EDA), and advanced statistical testing**. The workflow is deliberately linear and auditable so anyone can trace a finding back to the exact file and step that produced it.

**Tools used:** Excel (profiling, cleaning, EDA, tests) • Tableau (dashboards) • R (automation / extensions planned)

---

## 🧭 Workflow: Step-by-step (Data Quality → Analysis → Insights)


### 1. **Data Profiling**

* **Extracted file:** [docs/data_profiling.csv](docs/data_profiling.csv)
* **Tasks performed:** Checked data types, missing values, and duplicates. Generated summary statistics (mean, median, std for numerics; counts for categoricals). Logged missing-value counts by column.

---

### 2. **Consistency Checks**

* **Extracted file:** [docs/consistency_checks.csv](docs/consistency_checks.csv)
* **Tasks performed:** Logical validation (policy start ≤ end dates, premium ≥ 0, claim ≤ premium, realistic vehicle ages). Documented affected rows and corrective actions.

---

### 3. **Clean Dataset**

* **Extracted file:** [data_clean/Motor_Vehicle_Insurance_Data_AL.csv](data_clean/Motor_Vehicle_Insurance_Data_AL.xlxs)
* **Tasks performed:** Removed inconsistencies, enforced data types (dates, numerics), removed duplicates, and produced the **ready-to-use clean dataset** for further analysis.

---

### 4. **Exploratory Data Analysis (EDA)**

* **Extracted files:**

  * Continuous analysis → [analysis/EDA_CONT_Numerical.csv](analysis/EDA_CONT_Numerical.csv)
  * Discrete/categorical analysis → [analysis/Discrete_Numerical_Column.csv](analysis/Discrete_Numerical_Column.csv)

* **Tasks performed:**

  * **Continuous variables:** Explored premium distribution, claim costs, outliers, and skewness. Applied log transformations and binning where necessary.
  * **Categorical variables:** Examined driver count, policy risk categories, and sales channels, merging or re-labeling rare categories where appropriate.

---

## 5. Advanced Statistical Tests

All detailed descriptions and results for statistical tests are located in the **analysis** folder. Each test includes a short interpretation alongside its CSV output for quick inspection.

* [T-Test Results & Interpretation](analysis/t_test.md)
* [ANOVA Results & Interpretation](analysis/anova.md)
* [Chi-Square Results & Interpretation](analysis/chi_square.md)
* [Post-Hoc Test Results & Interpretation](analysis/post_hoc.md)


---

## 🔍 Key Findings

* **Premium vs. Risk:** Low-risk policies averaged **$143**, high-risk policies averaged **$327**.
* **Claims & Drivers:** Policies with a **second driver** were more likely to be high-risk.
* **Sales Channels & Retention:** Premiums vary across sales channels, implying channel-specific customer mixes and retention dynamics.

---

## 📊 Visualizations

Interactive dashboards were built in Tableau to visualize the above relationships (claims, premiums, channels, risk profiles).
👉 [Motor Vehicle Insurance Dashboard — Tableau Public](https://public.tableau.com/app/profile/emmanuel.agbo3961/viz/MotorVehicleInsuranceAnalytics/Dashboard1?publish=yes)

Screenshots of the dashboards are saved in the [visualizations](visualizations) folder for quick viewing.

---

## 🚀 Next Steps

* Expand into predictive modeling for claim likelihood and premium optimization.
* Automate the cleaning & EDA pipeline using **SQL or R** so future data ingests run like clockwork.
* Turn Tableau dashboards into scheduled reports or publish them to a hosted server for stakeholders.

---

## 👤 Author

**Emmanuel Agbo** — Data Analyst | Excel • SQL • Tableau • R

