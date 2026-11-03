# 🌟 Skill Nexis — Data Science & Analytics Internship Repository

[![Internship Portfolio](https://img.shields.io/badge/Internship-Data_Science_%26_Analytics-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](#-internship-milestones--technical-modules-matrix)
[![Power BI](https://img.shields.io/badge/Power_BI-Executive_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://github.com/durgesh261/Skill_Nexis-Week-4)
[![Python](https://img.shields.io/badge/Python-Data_Engineering_%26_ML-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-2)
[![SQL](https://img.shields.io/badge/SQL-Advanced_Queries-CC292B?style=for-the-badge&logo=mysql&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-2)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-3)
[![Excel](https://img.shields.io/badge/Excel-Financial_Modeling-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-1)

Welcome to the **Skill Nexis Data Science & Analytics Internship** project repository. This centralized hub documents the core data engineering, relational database querying, statistical modeling, machine learning pipelines, and executive business intelligence dashboards developed during my industry internship as a **Data Science & Analytics Intern** at **Skill Nexis** (AICTE & MSME Reg. • Certificate ID: `SNX-00683-26`).

Each functional phase is maintained in its own dedicated, standalone GitHub repository and synchronized within this workspace using Git submodules.

---

## 🗺️ Internship Milestones & Technical Modules Matrix

| Phase | Technical Module | Sub-Repository Link | Status | Key Deliverables & Engineering Focus |
| :---: | :--- | :---: | :---: | :--- |
| **Phase 1** | **Enterprise Data Cleaning, Statistical Auditing & Sales Dashboard** | [**`Skill_Nexis-Week-1`**](https://github.com/durgesh261/Skill_Nexis-Week-1) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • **Cleaned 51,290 Global Transactional Records** (`global_superstore_2016.xlsx`)<br>• Missing value imputation (41,296 null postal codes handled)<br>• Parametric statistical modeling (`AVERAGE`, `MEDIAN`, `MODE`, `VAR.S`)<br>• Executive Sales Performance Dashboard with 6 dynamic KPI cards |
| **Phase 2** | **Relational Data Engineering, SQL Analytics & Python Pipeline** | [**`Skill_Nexis-Week-2`**](https://github.com/durgesh261/Skill_Nexis-Week-2) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • Ingested and normalized multi-table database (7,617 transactional records)<br>• Python EDA pipeline (Pandas, multi-column sorting, correlation heatmaps)<br>• Advanced SQL query suite (`JOIN`, `CASE`, nested subqueries, aggregations)<br>• Customer Lifetime Value, Regional AOV & 10 analytical business queries |
| **Phase 3** | **Automated Data Wrangling, Time-Series Cleaning & Anomaly Correction** | [**`Skill_Nexis-Week-3`**](https://github.com/durgesh261/Skill_Nexis-Week-3) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • Automated ingestion and cleaning pipeline for messy recording logs<br>• Chronological timestamp reconstruction and date formatting (`20201226` -> ISO)<br>• Outlier remediation (sensor duration errors corrected) & median imputation<br>• 5 engineered health metrics & 5 publication-ready visualizations |
| **Phase 4** | **Capstone Project: Financial Predictive Modeling & Power BI Intelligence** | [**`Skill_Nexis-Week-4`**](https://github.com/durgesh261/Skill_Nexis-Week-4) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • Exploratory Data Analysis across $118.7M commercial transaction portfolio<br>• Supervised ML Regression ($R^2 = 0.9934$ OLS / $0.9841$ Random Forest)<br>• Enterprise Power BI Star Schema data model with 14 custom DAX measures<br>• Live interactive HTML5/Chart.js simulation dashboard & stakeholder briefing |

---

## 📊 Phase 1 Showcase: Enterprise Data Cleaning & Sales Dashboard

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-1](https://github.com/durgesh261/Skill_Nexis-Week-1)

- **Large-Scale Data Cleaning & Audit (`global_superstore_2016.xlsx` & `Week1_Practice_Assignment_Solutions.xlsx`)**:
  - **Dataset Scale**: **51,290 enterprise transactional records** across 24 attributes.
  - **Missing Value Handling**: Systematically handled 41,296 null entries in `Postal Code` by imputing `"N/A - Non-US"` without dropping international orders or biasing regional sales figures.
  - **Deduplication**: Verified 0 duplicate transactions across composite primary keys (`Order ID` + `Product ID`).
  - **Regional Sales Aggregation**: Western Europe led global revenue with **$1,731,929.74** (13.70% share).
  - **Parametric Statistics**: Computed global Mean order value ($246.49), Median ($85.05), Mode ($12.96), and Sample Variance (237,719.98).
- **Executive Sales Performance Dashboard (`Week1_Sales_Performance_Dashboard.xlsx`)**:
  - 6 KPI summary cards: Total Revenue **$12.64M**, Net Profit **$1.47M**, Profit Margin **11.61%**, AOV **$491.39**.
  - Multi-year trend visual showing **+90.31% cumulative revenue expansion** over the 4-year operating window.

---

## 🐍 Phase 2 Showcase: Relational Data Engineering & SQL Query Suite

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-2](https://github.com/durgesh261/Skill_Nexis-Week-2)

- **Python Analysis Pipeline (`Week2_Python_Data_Analysis.ipynb`)**:
  - Ingested multi-table transactional database (`chocolate_sales.csv`, 7,617 rows, 13 attributes).
  - Automated categorical data sanitization (imputed unassigned sales teams).
  - Category breakdown: **Bars** ($21.75M, 49.92%), **Bites** ($13.98M, 32.09%), **Other** ($7.84M, 17.99%).
  - Correlation analysis and visual matrix generation (`correlation_matrix.png`).
- **SQL Analytics Suite (`week2_sql_queries.sql` & `Week2_SQL_Query_Results.xlsx`)**:
  - Top representative evaluation: **Wilone O'Kielt** ($1,914,157.00 revenue, $6,214.80 AOV).
  - Country-level AOV rankings: **India ($5,797.19)**, **New Zealand ($5,755.35)**.
  - Formulated 10 complex analytical queries covering multi-table `JOIN`s, conditional `CASE` classifications, box-size threshold filters, and cross-border comparisons.

---

## 🏋️‍♂️ Phase 3 Showcase: Automated Data Wrangling & Feature Engineering

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-3](https://github.com/durgesh261/Skill_Nexis-Week-3)

- **Wrangling Pipeline (`data_cleaning.py` & `Week3_Python_Data_Wrangling.ipynb`)**:
  - Cleaned messy tracking records with formatting and logging irregularities (`dirty_data.csv`).
  - **Date Standardization**: Corrected corrupted integer dates (`20201226` -> `2020-12-26`) and imputed missing chronological records (`2020-12-22`).
  - **Sensor Outlier Remediation**: Detected and corrected typographical duration errors (`450` min -> `45` min).
  - **Median Imputation**: Imputed missing caloric values based on duration-stratified median heuristics.
  - **Feature Engineering**: Engineered 5 derived metrics (`Calories_Per_Minute`, `Heart_Rate_Spread`, `Workout_Intensity`, `Day_Name`, `Is_Weekend`).
- **Exploratory Visualizations (Matplotlib & Seaborn)**:
  - 5 publication-quality figures: `calories_vs_duration.png`, `workout_trends_december.png`, `pulse_distribution.png`, `workout_intensity_boxplot.png`, `correlation_heatmap.png`.

---

## 🏆 Phase 4 Showcase: Capstone Predictive Modeling & Power BI Intelligence

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-4](https://github.com/durgesh261/Skill_Nexis-Week-4)

- **Portfolio EDA & Business Diagnostics**:
  - Analyzed Microsoft Financial Sample dataset (700 global commercial transactions across North America & Europe).
  - Global Portfolio Metrics: **$118.73M Net Sales**, **$16.89M Net Profit** (14.23% margin), **1.13M Units Sold**.
  - **Segment Health Diagnostic**: Identified that Government contracts drive **67.4% of total profit ($11.39M)** at a **21.70% margin**, whereas Enterprise contracts operate at a **-$622K deficit (-3.17% margin)** due to uncapped discretionary discounting.
- **Supervised Machine Learning Sales Modeling**:
  - **Multiple Linear Regression (OLS)**: $R^2 = 0.9934$, RMSE = $19,121.49, MAE = $13,842.10.
  - **Random Forest Regressor (100 Trees)**: $R^2 = 0.9841$, RMSE = $29,667.59, MAE = $18,924.58.
  - Extracted feature importances identifying COGS (52.4%), Units Sold (28.1%), and Discounts (9.6%) as primary variance drivers.
- **Power BI Decision System & Dimensional Architecture**:
  - Star Schema model connecting central `FactFinancialSales` to 4 conformed dimension tables.
  - Implemented 14 production DAX measures (`[Total Sales]`, `[Profit Margin %]`, `[Sales YoY Growth %]`, etc.).
  - Interactive HTML5/Chart.js simulation (`dashboard_preview.html`) with real-time slicers and dynamic KPI cards.
- **Engineering Deliverables Package**:
  - 📗 `Week4_Financial_Analysis_Report.xlsx`: Multi-tab corporate financial dashboard.
  - 🐍 `Week4_Capstone_EDA_and_Regression.ipynb`: End-to-end Python exploratory & modeling notebook.
  - 📑 `Executive_Stakeholder_Presentation.md`: Strategic briefing with actionable commercial recommendations.
  - 📊 `DAX_Measures_and_Data_Model.md` & `dashboard_preview.html`: Complete Power BI model & interactive simulation.

---

## 📂 Repository Directory Layout

```
Skill_Nexis/ (Master Internship Portfolio Hub)
│
├── .gitmodules                     # Tracks all 4 submodule repositories
├── .gitignore
├── README.md                       # Master Internship Repository Documentation
│
├── Week-01/                        # Submodule: durgesh261/Skill_Nexis-Week-1 (Phase 1)
│   ├── Week1_Practice_Assignment_Solutions.xlsx (Cleaned_Data: 51,290 records)
│   ├── Week1_Sales_Performance_Dashboard.xlsx
│   ├── global_superstore_2016.xlsx (51,290 transactional records)
│   ├── build_assignment.py
│   ├── build_dashboard.py
│   └── README.md
│
├── Week-02/                        # Submodule: durgesh261/Skill_Nexis-Week-2 (Phase 2)
│   ├── data/ (awesome_chocolates.db, chocolate_sales.csv [7,617 rows], etc.)
│   ├── python_analysis/ (Week2_Python_Data_Analysis.ipynb, script, heatmap)
│   ├── sql_analysis/ (week2_sql_queries.sql, runner, query results)
│   └── README.md
│
├── Week-03/                        # Submodule: durgesh261/Skill_Nexis-Week-3 (Phase 3)
│   ├── data/ (dirty_data.csv, cleaned_data.csv)
│   ├── notebooks/ (Week3_Python_Data_Wrangling.ipynb)
│   ├── scripts/ (data_cleaning.py, data_visualization.py)
│   ├── visuals/ (5 Matplotlib & Seaborn charts)
│   └── README.md
│
└── Week-04/                        # Submodule: durgesh261/Skill_Nexis-Week-4 (Phase 4 Capstone)
    ├── data/ (financial_sample.xlsx, cleaned_financial_sample.csv)
    ├── notebooks/ (Week4_Capstone_EDA_and_Regression.ipynb)
    ├── powerbi_dashboard/ (DAX_Measures_and_Data_Model.md, dashboard_preview.html)
    ├── reports/ (Week4_Financial_Analysis_Report.xlsx, Executive_Stakeholder_Presentation.md)
    ├── scripts/ (eda_and_regression.py, build_excel_report.py, etc.)
    ├── visuals/ (7 EDA, regression & dashboard graphics)
    └── README.md
```

---

## 🚀 How to Clone & Reproduce

To clone this master repository and automatically initialize all sub-repositories:

```bash
git clone --recurse-submodules https://github.com/durgesh261/Skill_Nexis.git
```

---

## 👤 Author & Internship Details
- **Intern**: Durgesh ([@durgesh261](https://github.com/durgesh261))
- **Role**: Data Science & Analytics Intern
- **Organization**: Skill Nexis (AICTE & MSME Reg.)
- **Credential**: Certificate ID: `SNX-00683-26`
- **Verification**: Complete Source Code, Multi-format Deliverables & Production Dashboards Verified.
