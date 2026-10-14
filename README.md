# 🌟 Skill_Nexis — 4-Week Data Analyst Program

[![Program Progress](https://img.shields.io/badge/Progress-Week%201%20of%204%20Completed-brightgreen?style=for-the-badge)](#-weekly-sub-repositories-matrix)
[![Excel](https://img.shields.io/badge/Excel-Advanced-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/durgesh261/Skill_Nexis-Week-1)
[![SQL](https://img.shields.io/badge/SQL-Relational-CC292B?style=for-the-badge&logo=mysql&logoColor=white)](#)
[![Power BI](https://img.shields.io/badge/Power_BI-Interactive-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](#)
[![Python](https://img.shields.io/badge/Python-Data_Analytics-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)

Welcome to the **Skill_Nexis** Master Repository. This serves as the centralized portfolio and navigation hub for the complete **4-Week Data Analyst Program**. 

To maintain clean separation of concerns and production-ready modularity, each week's assignments, datasets, scripts, and dashboards are maintained in dedicated sub-repositories linked below.

---

## 🗺️ Weekly Sub-Repositories Matrix

| Week | Module Title | Sub-Repository Link | Status | Key Deliverables & Topics |
| :---: | :--- | :---: | :---: | :--- |
| **Week 1** | **Excel & Data Fundamentals** | [**`Skill_Nexis-Week-1`**](https://github.com/durgesh261/Skill_Nexis-Week-1) | ![Completed](https://img.shields.io/badge/Status-Completed-success) | • 5 Practice Questions Solved<br>• Data Cleaning (Duplicates & Nulls)<br>• Descriptive Statistics (`AVERAGE`, `MEDIAN`, `MODE`, `VAR.S`)<br>• Executive Sales Performance Dashboard |
| **Week 2** | **Advanced Excel, SQL & Relational Databases** | *(Upcoming Sub-Repo)* | ![Upcoming](https://img.shields.io/badge/Status-Upcoming-yellow) | • `XLOOKUP`, `INDEX` + `MATCH`<br>• Relational Queries, Joins & Aggregations<br>• Subqueries, CTEs & Window Functions<br>• Relational Analytics Project |
| **Week 3** | **Business Intelligence & Dashboards** | *(Upcoming Sub-Repo)* | ![Upcoming](https://img.shields.io/badge/Status-Upcoming-yellow) | • Power BI / Tableau Data Modeling<br>• DAX Measures & Calculated Columns<br>• Interactive Visual Dashboards & Slicers<br>• Business KPI Reporting |
| **Week 4** | **Python for Data Analysis & Capstone** | *(Upcoming Sub-Repo)* | ![Upcoming](https://img.shields.io/badge/Status-Upcoming-yellow) | • Pandas & NumPy Data Wrangling<br>• Exploratory Data Analysis (EDA)<br>• Matplotlib & Seaborn Visualizations<br>• Final Comprehensive Capstone Report |

---

## 📊 Week 1 Showcase: Excel & Data Fundamentals

> **Full Sub-Repository**: 🔗 [https://github.com/durgesh261/Skill_Nexis-Week-1](https://github.com/durgesh261/Skill_Nexis-Week-1)

### 1. Practice Assignment Solutions (`Week1_Practice_Assignment_Solutions.xlsx`)
- **Q1: Data Cleaning**: Confirmed **0 duplicates** across 51,290 records. Handled **41,296 null entries in `Postal Code`** by imputing `"N/A - Non-US"` (preserving non-US global transactions).
- **Q2: Regional Sales Pivot**: Aggregated revenue for all 23 global regions. Western Europe leads globally with **$1,731,929.74** (13.70% share).
- **Q3: Descriptive Statistics**: Live dynamic formulas for `Sales`, `Profit`, `Quantity`, and `Discount`:
  - Mean Sales: **$246.49** | Median Sales: **$85.05** | Mode Sales: **$12.96** | Sample Variance: **237,719.98**
- **Q4: Conditional Formatting**: Highlighted Top 10 highest sales orders using native Excel Top 10 rules.
- **Q5: Category Revenue Chart**: Clustered chart showing Technology ($4.74M), Furniture ($4.11M), and Office Supplies ($3.79M).

### 2. Executive Sales Performance Dashboard (`Week1_Sales_Performance_Dashboard.xlsx`)
- 💰 **Total Revenue**: `$12,642,502` *(+26.3% YoY growth in 2015)*
- 📈 **Total Profit**: `$1,467,457` *(11.61% overall net margin)*
- 📦 **Total Orders**: `25,728` unique orders *(51,290 items)*
- 🏷️ **Average Order Value**: `$491.39` per order
- 📉 **4-Year Yearly Trend**: Revenue climbed steadily from $2.26M (2012) to $4.30M (2015) — **+90.31% cumulative expansion**.
- 👥 **Department / Customer Segments**: Consumer (51.5%), Corporate (30.3%), Home Office (18.3%).

---

## 📂 Repository Structure

```
Skill_Nexis/ (Master Repository)
│
├── .gitmodules                     # Git submodule tracking Week 1 sub-repo
├── .gitignore
├── README.md                       # Master 4-Week Program Portal
│
└── Week-01/                        # Linked Sub-Repository (durgesh261/Skill_Nexis-Week-1)
    ├── Week1_Practice_Assignment_Solutions.xlsx
    ├── Week1_Sales_Performance_Dashboard.xlsx
    ├── global_superstore_2016.xlsx
    ├── build_assignment.py
    ├── build_dashboard.py
    └── README.md
```

---

## 🚀 How to Clone & Access

To clone this master repository along with the weekly sub-repositories:

```bash
git clone --recurse-submodules https://github.com/durgesh261/Skill_Nexis.git
```

Or access each sub-repository directly from the [Weekly Matrix](#-weekly-sub-repositories-matrix) above.

---

## 👤 Author
- **Durgesh** ([@durgesh261](https://github.com/durgesh261))
- **Program**: Data Analyst Course (4-Week Curriculum)
