# 🧾 Loan Default Analysis Dashboard (Power BI)

This project presents an interactive Power BI dashboard to analyze **loan default trends**, **financial risk metrics**, and **demographic patterns** using a comprehensive dataset. It leverages time intelligence, DAX measures, and visual storytelling to uncover key business insights.

📊 **Live Dashboard**:  
[Click to view in Power BI Service](https://app.powerbi.com/reportEmbed?reportId=4c55bdba-7b56-498a-b7fd-d322629ea446&autoAuth=true&ctid=e1d99821-ef38-4f48-836f-7a7ca113dab7)

---

## 📦 Project Overview

The Power BI report is built using a **structured ETL and modeling pipeline** that includes:

- **Data Cleaning**: Handled using **MySQL Server** to remove nulls, fix inconsistencies, and prepare structured tables.
- **Data Integration**: Loaded into **Power BI via Dataflows**, ensuring reusable and centralized ETL logic.
- **Data Modeling**: Built a **star schema** with fact and dimension tables.
- **Measures and KPIs**: Created multiple **DAX measures** under different categories like:
  - Loan Amount Analysis
  - Default Rate Analysis
  - Time Series Analysis
  - Credit Score and Education Impact

---

## 🔍 Key Dashboard Sections

### 📍 Page 1: **Loan Default and Overview**
- **Loan Amount by Purpose & Employment Type**
- **Default Rate (%) by Year & Employment Type**
- **Average Loan Amount by Age Group**

### 📍 Page 2: **Applicant Demographics & Financial Profile**
- **Loan Distribution by Credit Score, Education, and Age**
- **Donut and Line Charts** showing:
  - Marital Status
  - Dependents
  - Mortgage

### 📍 Page 3: **Financial Risk Metrics**
- **YOY Loan Amount Change**
- **Total Default Loans by Year**
- **YTD Loan Analysis by Credit Score + Marital Status**
- **Sankey Diagrams** to visualize flow between Income Brackets and Loan Distribution

---

## 🧠 Technologies Used

| Tool / Language      | Purpose                               |
|----------------------|----------------------------------------|
| **MySQL Server**     | Data cleaning and transformation       |
| **Power BI Desktop** | Data modeling, visuals, and reporting  |
| **Power BI Dataflows** | Centralized data extraction & loading |
| **Bravo BI**         | Time intelligence DAX & performance tuning |
| **DAX**              | Measures, KPIs, and calculated columns |

---

## 🧮 Time Intelligence Measures

Created using **Bravo BI**:
- YOY Loan Amount Change
- YOY Default Loan Change
- To-date Growth
- Moving Annual Growth
- Total Defaults (YTD)
- Loan Growth over full period

---

## 🗃 Data Sources

- Primary dataset stored and processed in **MySQL**
- Connected to Power BI using **Power BI Dataflows**
- Measures categorized into 3 folders:
  - **ALL MEASURES-1**: Purpose, Age, Employment
  - **ALL MEASURES-2**: Credit score, Education
  - **ALL MEASURES-3**: Time-based metrics and totals

---

## ✅ Highlights

- End-to-end data pipeline from raw data to insights
- Custom measures for business-relevant KPIs
- Visually appealing and intuitive UI
- Applied data storytelling principles
- Optimized report using **Bravo BI**

---



## 📩 Contact

**Anuj Agarwal**  
Data Analyst | BI Developer  


---

> ⭐ If you like this dashboard, feel free to clone, modify, and share!
