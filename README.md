# 💫 Google sheets | Utilizing Spreadsheets for Data Analytics
This project is an analytical dashboard built in Google Sheets using a simplified version of the AdventureWorks dataset, including sales orders, sales reasons, employees, and sales territories.

The goal of this analysis is to transform raw transactional data into actionable business insights. The dataset has been partially cleaned and optimized for performance, but still requires thoughtful handling of potential redundancies and relationships between tables.

The analysis follows a structured data analytics approach (Ask → Prepare → Process → Analyze → Share → Act) and focuses on answering key business questions such as sales performance trends, online vs non-online order distribution, delivery performance, top-performing salespeople, geographic performance, and the most impactful sales drivers.

The final output is an interactive “Overview” dashboard designed for business stakeholders, including pivot tables, charts, and dynamic analysis tools. The project demonstrates practical skills in data structuring, analysis, visualization, and business storytelling using Google Sheets.

---

**🌱 Skills demonstrated:**

- Data analysis using structured methodology (Ask–Prepare–Process–Analyze–Share–Act)
- Data cleaning and transformation in Google Sheets
- Pivot tables and data aggregation
- Data visualization and dashboard creation
- Trend and comparative analysis (sales trends, online vs offline)
- Lookup functions (VLOOKUP)
- Data validation and conditional formatting
- Business insight generation and reporting
- Advanced spreadsheet functions (ARRAYFORMULA, IF, CONCATENATE)

---

## 🧱 Structure of Portfolio

This Google Sheets project is structured into clear layers: task definition, data preparation, analysis, and final dashboard presentation.

**1. Task Sheet**
This sheet contains the full assignment description and analytical requirements. It defines the business questions that guided the entire analysis process and ensures a structured and structured approach to solving the problem.

**2. Data Layer (Raw & Processed Data)**
The dataset is based on the AdventureWorks database and includes multiple interconnected tables:

AdventureWorks.SalesOrderHeader – main transactional dataset, enriched with additional fields and standardized formats
AdventureWorks.Employee – salesperson information and contact details
AdventureWorks.SalesReason – reasons behind customer purchase decisions
AdventureWorks.SalesTerritory – geographic and country-level sales data
Support Sheet (Pivot Tables) – intermediate aggregation layer used to build dashboard visualizations

This layer includes cleaned, formatted, and structured data used for analysis.

**3. Analysis & Pivot Layer**

A dedicated pivot table layer was created to aggregate and structure the data for reporting. These pivot tables serve as the foundation for all visualizations in the dashboard.

**4. Overview Dashboard (Main Output)**

The Overview sheet summarizes key business insights through visual analysis:

Sales Performance: *Monthly revenue, volume, and average trends*
Customer Behavior: *Sales reasons analysis by quarter*
Channel Analysis: *Online vs non-online sales comparison (revenue & volume)*
Performance Leaders: *Top employees by revenue and transaction count*
Geographic Analysis: *Sales trends by country over time*
Delivery Performance: *Order-to-ship time analysis*

The dashboard is designed to provide a clear, executive-level view of business performance and decision-making insights.

---

## 🌍 Table of Contents

- [Data Source](#-data-source)
- [Utilizing Spreadsheets for Data Analytics](#-utilizing-spreadsheets-for-data-analytics)
- [Technologies](#-technologies)
- [Usage Instructions](#-usage-instructions)
- [Next Steps](#-next-steps)

---

## 🧳 Data Source

The queries are based on the **AdventureWorks 2005** demo database provided by Microsoft.

You can download the dataset here:  
[Microsoft Learn AdventureWorks Samples](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver17)

---

## ⭐ Utilizing Spreadsheets for Data Analytics

👉 Explore the full interactive dashboard here:  
[Open Google Sheets Analysis](https://docs.google.com/spreadsheets/d/1mApP8pBNMbM7zQDyxo1rOAOa28LwwZZZBhNEhXW7PyM/edit?gid=141689769#gid=141689769)

---

## 💻 Technologies

- Google Sheets
- Pivot Tables
- Data Visualization (Charts)
- Spreadsheet Functions (VLOOKUP, IF, ARRAYFORMULA, CONCATENATE)
- Data Cleaning & Transformation Techniques
- Conditional Formatting & Data Validation

---

## 🔎 Usage Instructions

1. Open the Google Sheets dashboard using the provided link
2. Navigate through different sheets:
- Task Sheet for assignment context
- Data sheets for raw and processed datasets
- Pivot tables for structured aggregations
- Overview dashboard for final insights
3. Review charts and insights to understand business performance trends

---

## ❔ Next Steps

- Expand dashboard with additional KPIs and deeper segmentation (e.g. product-level analysis)
- Add automation using Apps Script or advanced formulas
- Integrate additional data sources for more comprehensive analysis
- Recreate the project in Power BI or Tableau for cross-tool comparison
- Develop similar case studies to strengthen portfolio (finance, HR, or operations datasets)
