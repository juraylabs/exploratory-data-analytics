# 🔍 Exploratory Data Analysis (SQL)

## 📌 Overview
This repository contains a structured set of SQL scripts used to perform **exploratory data analysis (EDA)** on a relational dataset covering customers, products, and transactional measures.

The analysis focuses on:
- 🗂️ Understanding database structure and data coverage  
- ✅ Validating dimensions, measures, and time ranges  
- 📊 Analyzing scale, rankings, trends, and cumulative behavior  
- 🧩 Segmenting entities and evaluating relative performance  
- 📈 Producing reporting-ready customer and product outputs  

The scripts are ordered intentionally to reflect a real-world analytical workflow.

---

## 🧭 Analytical Workflow
The analysis follows a progressive sequence:

1. 🏗️ Database and schema inspection  
2. 🧪 Dimension and measure validation  
3. ⏱️ Temporal coverage analysis  
4. 📏 Magnitude and ranking analysis  
5. 📉 Trend, cumulative, and performance evaluation  
6. 🧠 Segmentation and contribution analysis  
7. 📦 Final reporting outputs  

Each step builds confidence in the data before advancing to higher-level insights.

---

## 🗃️ Script Breakdown

### 00_init_database.sql
🏁 Initial database inspection and schema discovery.

### 01_database_exploration.sql
🔎 High-level table exploration and row count validation.

### 02_dimensions_exploration.sql
🧩 Analysis of categorical dimensions, cardinality, and null coverage.

### 03_date_range_exploration.sql
📅 Validation of temporal coverage and continuity.

### 04_measures_exploration.sql
📐 Inspection of numeric measures, ranges, and potential anomalies.

### 05_magnitude_analysis.sql
📊 Evaluation of scale and distribution across key entities.

### 06_ranking_analysis.sql
🏆 Ranking of customers and products by primary performance metrics.

### 07_change_over_time_analysis.sql
📈 Trend analysis and period-over-period behavior.

### 08_cumulative_analysis.sql
➕ Running totals and cumulative contribution analysis.

### 09_performance_analysis.sql
⚖️ Comparative performance analysis across dimensions and time.

### 10_data_segmentation.sql
🧠 Segmentation of entities based on behavioral or performance criteria.

### 11_part_to_whole_analysis.sql
🧮 Contribution-to-total analysis and concentration patterns.

### 12_report_customers.sql
👥 Customer-level aggregated outputs suitable for reporting or dashboards.

### 13_report_products.sql
📦 Product-level aggregated outputs suitable for reporting or dashboards.

---

## 📊 Visualization Layer (BI Tools)
The reporting outputs from this analysis are designed to serve as **direct inputs for BI tools** such as **Tableau, Power BI, or Qlik**.

Typical visualization use cases include:
- 📈 Time-series trends (revenue, volume, performance over time)
- 🏆 Top-N rankings (customers, products, categories)
- 🧩 Segment comparisons and contribution analysis
- 📊 Cumulative and part-to-whole views

Recommended approach:
- Materialize reporting queries (`12_` and `13_`) as database views
- Connect BI tools directly to these views
- Keep business logic in SQL and visualization logic in the BI layer

This separation ensures consistency, performance, and reusability across dashboards.

---

## 🛠️ Usage Notes
- ▶️ Scripts are designed to be run sequentially.
- 🔧 Table and column names may require adjustment depending on environment.
- 📤 Reporting scripts are suitable for export or BI consumption.

---

## 🎯 Portfolio Context
This repository demonstrates how I approach exploratory data analysis in SQL when working with an unfamiliar dataset.

The focus is on:
- 🧱 Structuring analysis in a logical, repeatable sequence  
- 🔍 Validating data quality before drawing conclusions  
- 🔄 Translating raw tables into reporting-ready outputs  
- ✍🏽 Writing readable, maintainable SQL aligned with real analytics workflows  

The patterns used here reflect how I analyze data in production environments prior to dashboarding, modeling, or downstream automation.

---

## 🚀 Next Steps
- 📊 Build dashboards in Tableau, Power BI, or Qlik using reporting views  
- 🐍 Extend analysis with Python for deeper statistical insights  
- 🧪 Add data quality checks and validation queries  

## 👋 About Me
More of my work: [github.com/juraylabs](https://github.com/juraylabs)
