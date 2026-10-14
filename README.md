# 🌟 Skill_Nexis — 4-Week Data Analyst Program

[![Program Progress](https://img.shields.io/badge/Progress-Week%201%2C%202%20%26%203%20of%204%20Completed-brightgreen?style=for-the-badge)](#-weekly-sub-repositories-matrix)
[![Excel](https://img.shields.io/badge/Excel-Advanced-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-1)
[![Python](https://img.shields.io/badge/Python-Data_Analytics-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-2)
[![SQL](https://img.shields.io/badge/SQL-Advanced-CC292B?style=for-the-badge&logo=mysql&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-2)
[![Data Wrangling](https://img.shields.io/badge/Pandas-Data_Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-3)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-388E3C?style=for-the-badge&logo=python&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-3)

Welcome to the **Skill_Nexis** Master Repository. This acts as the centralized portfolio and navigation portal for the complete **4-Week Data Analyst Program**.

Each module is maintained in its own dedicated, standalone repository to ensure clean organization, independent dataset management, and direct reproducibility.

---

## 🗺️ Weekly Sub-Repositories Matrix

| Week | Module Title | Sub-Repository Link | Status | Key Deliverables & Topics Covered |
| :---: | :--- | :---: | :---: | :--- |
| **Week 1** | **Excel & Data Fundamentals** | [**`Skill_Nexis-Week-1`**](https://github.com/durgesh261/Skill_Nexis-Week-1) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • 5 Practice Assignment Questions Solved<br>• Data Cleaning (Duplicates & Nulls)<br>• Descriptive Statistics (`AVERAGE`, `MEDIAN`, `MODE`, `VAR.S`)<br>• Executive Sales Performance Dashboard |
| **Week 2** | **Python & SQL for Data Analysis** | [**`Skill_Nexis-Week-2`**](https://github.com/durgesh261/Skill_Nexis-Week-2) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • 5 Python Practice Questions (Pandas & Seaborn)<br>• Data Cleaning, Grouping & Multi-Column Sorting<br>• Correlation Matrix & Heatmap Visual<br>• SQL Query Suite (`SELECT`, `JOIN`, `CASE`, Subqueries)<br>• Top Customers & AOV Analytics + 10 Challenge Problems |
| **Week 3** | **Python & Data Wrangling** | [**`Skill_Nexis-Week-3`**](https://github.com/durgesh261/Skill_Nexis-Week-3) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • Messy Dataset Cleaning (Missing Dates, Outliers & Nulls)<br>• 5 Engineered Features (`Calories/Min`, `HR Spread`, etc.)<br>• Analytical Row Filtering (High Calorie, Peak HR)<br>• Matplotlib & Seaborn Visualizations (5 Figures) |
| **Week 4** | **Python for Data Analysis & Capstone** | *(Upcoming Sub-Repo)* | ![Upcoming](https://img.shields.io/badge/Status-Upcoming-yellow) | • Exploratory Data Analysis (EDA) & Modeling<br>• Advanced Statistical Testing<br>• Interactive Dashboard Reporting<br>• Final Capstone Portfolio Project |

---

## 📊 Week 1 Showcase: Excel & Data Fundamentals

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-1](https://github.com/durgesh261/Skill_Nexis-Week-1)

- **Practice Assignment (`Week1_Practice_Assignment_Solutions.xlsx`)**:
  - Imputed 41,296 null entries in `Postal Code` with `"N/A - Non-US"` without data loss.
  - Region-wise Sales Pivot: Western Europe leads globally with **$1,731,929.74** (13.70% share).
  - Calculated Mean ($246.49), Median ($85.05), Mode ($12.96), and Variance (237,719.98).
  - Applied native Top 10 Conditional Formatting rules and category-wise bar chart.
- **Executive Sales Performance Dashboard (`Week1_Sales_Performance_Dashboard.xlsx`)**:
  - 6 KPI summary cards: Total Revenue **$12.64M**, Total Profit **$1.47M**, Profit Margin **11.61%**, AOV **$491.39**.
  - 4-Year Yearly Trend line chart showing **+90.31% cumulative growth**.

---

## 🐍 Week 2 Showcase: Python & SQL for Data Analysis

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-2](https://github.com/durgesh261/Skill_Nexis-Week-2)

- **Python Analysis (`Week2_Python_Data_Analysis.ipynb`)**:
  - Loaded `chocolate_sales.csv` (7,617 rows, 13 attributes).
  - Handled missing values (imputed 1,203 `Team` entries with `'Unassigned'`).
  - Category grouping: **Bars** ($21.75M, 49.92%), **Bites** ($13.98M, 32.09%), **Other** ($7.84M, 17.99%).
  - Multi-column sorting and correlation matrix visual (`correlation_matrix.png`).
- **SQL Analysis (`week2_sql_queries.sql` & `Week2_SQL_Query_Results.xlsx`)**:
  - Top rep: **Wilone O'Kielt** ($1,914,157.00 revenue, $6,214.80 AOV).
  - AOV by Country: **India ($5,797.19)**, **New Zealand ($5,755.35)**.
  - Solved all 10 Challenge Practice Problems (Milk Bars vs Eclairs, bulk shipments, India vs Australia).

---

## 🏋️‍♂️ Week 3 Showcase: Python & Data Wrangling

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-3](https://github.com/durgesh261/Skill_Nexis-Week-3)

- **Assignment Highlights (`data_cleaning.py` & `Week3_Python_Data_Wrangling.ipynb`)**:
  - Cleaned messy fitness dataset (`dirty_data.csv`).
  - **Date Standardization**: Fixed date format inconsistencies (`20201226`) and imputed missing chronological timestamp (`2020-12-22`).
  - **Outlier Correction**: Detected and corrected typographical error in `Duration` (`450` -> `45` min).
  - **Median Imputation**: Imputed missing `Calories` using duration-specific medians.
  - **Deduplication**: Eliminated duplicate workout session, resulting in 31 clean records.
  - **Feature Engineering**: Created 5 new attributes (`Calories_Per_Minute`, `Heart_Rate_Spread`, `Workout_Intensity`, `Day_Name`, `Is_Weekend`).
  - **Row Filtering**: Filtered high-calorie workouts (> 300 kcal: 12 sessions) and peak cardio workouts (Maxpulse >= 140: 4 sessions).
- **Exploratory Visualizations (Matplotlib & Seaborn)**:
  - `calories_vs_duration.png` (Regression scatter plot)
  - `workout_trends_december.png` (Timeline progression)
  - `pulse_distribution.png` (Heart rate distribution & KDE)
  - `workout_intensity_boxplot.png` (Intensity tier boxplot)
  - `correlation_heatmap.png` (Metrics correlation matrix)

---

## 📂 Repository Directory Layout

```
Skill_Nexis/ (Master Portfolio Hub)
│
├── .gitmodules                     # Tracks weekly sub-repositories
├── .gitignore
├── README.md                       # Master 4-Week Program Navigation Portal
│
├── Week-01/                        # Sub-Repository: durgesh261/Skill_Nexis-Week-1
│   ├── Week1_Practice_Assignment_Solutions.xlsx
│   ├── Week1_Sales_Performance_Dashboard.xlsx
│   ├── global_superstore_2016.xlsx
│   ├── build_assignment.py
│   ├── build_dashboard.py
│   └── README.md
│
├── Week-02/                        # Sub-Repository: durgesh261/Skill_Nexis-Week-2
│   ├── data/ (awesome_chocolates.db, chocolate_sales.csv, etc.)
│   ├── python_analysis/ (Week2_Python_Data_Analysis.ipynb, script, heatmap)
│   ├── sql_analysis/ (week2_sql_queries.sql, runner, query results)
│   └── README.md
│
└── Week-03/                        # Sub-Repository: durgesh261/Skill_Nexis-Week-3
    ├── data/ (dirty_data.csv, cleaned_data.csv)
    ├── notebooks/ (Week3_Python_Data_Wrangling.ipynb)
    ├── scripts/ (data_cleaning.py, data_visualization.py)
    ├── visuals/ (5 Matplotlib & Seaborn charts)
    └── README.md
```

---

## 🚀 How to Clone the Entire Portfolio

To clone this master repository and automatically pull all weekly sub-repositories:

```bash
git clone --recurse-submodules https://github.com/durgesh261/Skill_Nexis.git
```

---

## 👤 Author & Course Details
- **Author**: Durgesh ([@durgesh261](https://github.com/durgesh261))
- **Program**: Data Analyst Course (4-Week Professional Curriculum)
