# 🌟 Skill_Nexis — 4-Week Data Analyst Program

[![Program Progress](https://img.shields.io/badge/Progress-Week%201%20%26%202%20of%204%20Completed-brightgreen?style=for-the-badge)](#-weekly-sub-repositories-matrix)
[![Excel](https://img.shields.io/badge/Excel-Advanced-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-1)
[![Python](https://img.shields.io/badge/Python-Data_Analytics-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-2)
[![SQL](https://img.shields.io/badge/SQL-Advanced-CC292B?style=for-the-badge&logo=mysql&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-2)
[![Power BI](https://img.shields.io/badge/Power_BI-Interactive-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](#)

Welcome to the **Skill_Nexis** Master Repository. This acts as the centralized portfolio and navigation portal for the complete **4-Week Data Analyst Program**.

Each module is maintained in its own dedicated, standalone repository to ensure clean organization, independent dataset management, and direct reproducibility.

---

## 🗺️ Weekly Sub-Repositories Matrix

| Week | Module Title | Sub-Repository Link | Status | Key Deliverables & Topics Covered |
| :---: | :--- | :---: | :---: | :--- |
| **Week 1** | **Excel & Data Fundamentals** | [**`Skill_Nexis-Week-1`**](https://github.com/durgesh261/Skill_Nexis-Week-1) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • 5 Practice Assignment Questions Solved<br>• Data Cleaning (Duplicates & Nulls)<br>• Descriptive Statistics (`AVERAGE`, `MEDIAN`, `MODE`, `VAR.S`)<br>• Executive Sales Performance Dashboard |
| **Week 2** | **Python & SQL for Data Analysis** | [**`Skill_Nexis-Week-2`**](https://github.com/durgesh261/Skill_Nexis-Week-2) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • 5 Python Practice Questions (Pandas & Seaborn)<br>• Data Cleaning, Grouping & Multi-Column Sorting<br>• Correlation Matrix & Heatmap Visual<br>• SQL Query Suite (`SELECT`, `JOIN`, `CASE`, Subqueries)<br>• Top Customers & AOV Analytics + 10 Challenge Problems |
| **Week 3** | **Business Intelligence & Dashboards** | *(Upcoming Sub-Repo)* | ![Upcoming](https://img.shields.io/badge/Status-Upcoming-yellow) | • Power BI / Tableau Data Modeling<br>• DAX Measures & Calculated Columns<br>• Interactive Visual Dashboards & Slicers<br>• Business KPI Reporting |
| **Week 4** | **Python for Data Analysis & Capstone** | *(Upcoming Sub-Repo)* | ![Upcoming](https://img.shields.io/badge/Status-Upcoming-yellow) | • Exploratory Data Analysis (EDA) & Modeling<br>• Advanced Statistical Testing<br>• Matplotlib & Plotly Interactive Charts<br>• Final Capstone Portfolio Project |

---

## 📊 Week 1 Showcase: Excel & Data Fundamentals

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-1](https://github.com/durgesh261/Skill_Nexis-Week-1)

- **Practice Assignment (`Week1_Practice_Assignment_Solutions.xlsx`)**:
  - Imputed 41,296 null entries in `Postal Code` with `"N/A - Non-US"` without data loss.
  - Region-wise Sales Pivot: Western Europe leads globally with **$1,731,929.74** (13.70% share).
  - Calculated Mean ($246.49), Median ($85.05), Mode ($12.96), and Variance (237,719.98).
  - Applied native Top 10 Conditional Formatting rules.
  - Category-wise revenue bar chart.
- **Executive Sales Performance Dashboard (`Week1_Sales_Performance_Dashboard.xlsx`)**:
  - 6 KPI summary cards: Total Revenue **$12.64M**, Total Profit **$1.47M**, Profit Margin **11.61%**, AOV **$491.39**.
  - 4-Year Yearly Trend line chart showing **+90.31% cumulative growth**.

---

## 🐍 Week 2 Showcase: Python & SQL for Data Analysis

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-2](https://github.com/durgesh261/Skill_Nexis-Week-2)

### 1. Python for Data Analysis (`Week2_Python_Data_Analysis.ipynb` & script)
- **Q1 (Data Loading & Inspection)**: Loaded `chocolate_sales.csv` (7,617 rows, 13 attributes). Inspected with `shape`, `head()`, `info()`, `dtypes`, and `describe()`.
- **Q2 (Data Cleaning)**: Imputed 1,203 missing entries in `Team` with `'Unassigned'`. Verified 0 duplicate rows.
- **Q3 (Category Revenue)**: Grouped by category:
  - **Bars**: $21,746,501.00 (49.92% share, 1,435,141 boxes)
  - **Bites**: $13,978,391.00 (32.09% share, 848,184 boxes)
  - **Other**: $7,836,654.00 (17.99% share, 617,986 boxes)
  - **Total**: **$43,561,546.00**
- **Q4 (Multi-Column Sorting)**: Sorted by `['Category', 'Amount']` and `['Country', 'SaleDate']`. Top single transaction: **Van Tuxwell** in New Zealand (**$27,146.00**).
- **Q5 (Correlation Matrix & Heatmap)**: Analyzed correlation across `Amount`, `Customers`, `Boxes`, and `Cost_per_box`. Strong correlation of **0.7963** between `Amount` and `Boxes`. Visual heatmap exported as `correlation_matrix.png`.

### 2. SQL for Data Analysis (`week2_sql_queries.sql` & Excel export)
- **Database Engine**: Awesome Chocolates database loaded into standalone SQLite (`awesome_chocolates.db`) & raw MySQL dump (`awesome-chocolates-data.sql`).
- **Core Assignment (Top Customers & Average Order Value)**:
  - Top rep: **Wilone O'Kielt** (Delish, Hyderabad) with **$1,914,157.00** in total revenue across 308 orders ($6,214.80 AOV).
  - Global AOV: **$5,718.99** per shipment.
  - Highest AOV by Country: **India ($5,797.19)**, followed by New Zealand ($5,755.35) and Australia ($5,755.27).
- **10 Challenge Practice Problems Solved**:
  - Eclairs vs. Milk Bars (Eclairs leads in overall boxes: 144,651 vs. 130,995).
  - Monthly bulk shipments (> 1,000 boxes).
  - India vs. Australia monthly sales comparison.
  - Full output exported to **`Week2_SQL_Query_Results.xlsx`**.

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
└── Week-02/                        # Sub-Repository: durgesh261/Skill_Nexis-Week-2
    ├── data/
    │   ├── awesome-chocolates-data.sql
    │   ├── awesome_chocolates.db
    │   ├── chocolate_sales.csv
    │   └── setup_database.py
    ├── python_analysis/
    │   ├── Week2_Python_Data_Analysis.ipynb
    │   ├── week2_python_analysis.py
    │   └── correlation_matrix.png
    ├── sql_analysis/
    │   ├── week2_sql_queries.sql
    │   ├── run_sql_analysis.py
    │   └── Week2_SQL_Query_Results.xlsx
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
