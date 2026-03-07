# 📊 Sales Performance Dashboard — Excel Business Intelligence

<div align="center">

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-0078D4?style=for-the-badge&logo=databricks&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-FF6B35?style=for-the-badge&logo=powerbi&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

<br/>

> **Transforming raw Superstore data into actionable business intelligence through Excel's advanced analytics capabilities — delivering insights that drive strategic decision-making.**

<br/>

![Dashboard Preview](https://github.com/user-attachments/assets/a48bc2d1-54d0-4ae6-9cb7-0c5ed20138ca)

</div>

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem Statement](#-business-problem-statement)
- [Key Performance Metrics](#-key-performance-metrics)
- [Technical Architecture](#-technical-architecture)
- [Data Pipeline](#-data-pipeline)
- [Dashboard Features](#-dashboard-features)
- [Analytical Insights](#-analytical-insights)
- [Skills Demonstrated](#-skills-demonstrated)
- [How to Use](#-how-to-use)
- [Dataset](#-dataset)

---

## 🔍 Project Overview

This project delivers a **production-grade, interactive Sales Performance Dashboard** built entirely in Microsoft Excel, leveraging the Superstore Sales Dataset from Kaggle. The solution transforms 9,994+ transactional records into a consolidated BI dashboard that surfaces critical revenue patterns, regional disparities, and category-level performance trends.

The dashboard empowers stakeholders to:
- Monitor real-time KPIs across sales, units, and profitability
- Drill down by region, category, and time period via interactive slicers
- Track Month-over-Month (MoM) and Year-over-Year (YoY) growth trajectories
- Identify top-performing segments and underperforming areas requiring intervention

---

## 💼 Business Problem Statement

> *"Organizations accumulate vast transactional data but lack structured reporting mechanisms to convert it into strategic intelligence."*

**Challenge:** Raw sales data across 4 regions, 3 product categories, and multiple sub-categories resided in flat CSV format — unstructured, unanalyzed, and unusable for decision-making.

**Solution:** Designed an end-to-end data analysis pipeline culminating in an executive-grade dashboard that delivers clarity, interactivity, and measurable business value.

---

## 📈 Key Performance Metrics

| Metric | Description | Analysis Type |
|---|---|---|
| 💰 **Total Revenue** | Aggregate sales across all regions & categories | Cumulative + Trend |
| 📦 **Units Sold** | Volume analysis by category and time period | Segmented |
| 📅 **Monthly Sales Trend** | Revenue patterns across months | Time Series |
| 🗺️ **Regional Performance** | Comparative analysis across East, West, Central, South | Geographic |
| 🏷️ **Category Breakdown** | Technology, Furniture, Office Supplies performance | Categorical |
| 📊 **MoM Growth** | Month-over-Month revenue change percentage | Trend Analysis |
| 📆 **YoY Growth** | Year-over-Year performance comparison | Benchmark |

---

## 🏗️ Technical Architecture

```
Raw Dataset (CSV)
        │
        ▼
┌───────────────────┐
│   Data Ingestion  │  → Import & format validation
└────────┬──────────┘
         │
         ▼
┌───────────────────┐
│  Data Cleaning    │  → Null handling, type casting, deduplication
└────────┬──────────┘
         │
         ▼
┌───────────────────┐
│  Data Modeling    │  → Structured Excel Tables, calculated columns
└────────┬──────────┘
         │
         ▼
┌───────────────────┐
│  Pivot Analysis   │  → PivotTables with aggregated KPIs
└────────┬──────────┘
         │
         ▼
┌───────────────────┐
│  Visualization    │  → Pivot Charts, slicers, conditional formatting
└────────┬──────────┘
         │
         ▼
┌───────────────────┐
│  Dashboard Layer  │  → Executive-ready interactive BI dashboard
└───────────────────┘
```

---

## 🔄 Data Pipeline

### Phase 1 — Data Ingestion & Validation
- Imported raw Superstore dataset (`.csv`) into Excel
- Validated schema integrity: column headers, data types, row counts
- Identified and flagged null values, duplicate entries, and outliers

### Phase 2 — Data Cleaning & Transformation
- Standardized date formats to `MM/YYYY` for time-series aggregation
- Resolved inconsistent categorical labels (e.g., region/sub-category spellings)
- Engineered calculated columns:
  - `Order Month`, `Order Year` — extracted from Order Date
  - `Revenue Contribution %` — per-row share of total revenue
  - `Profit Margin %` — calculated from Sales and Profit fields

### Phase 3 — Data Modeling
- Structured raw data into formal **Excel Tables** for dynamic range management
- Built normalized summary tables as Pivot Table data sources

### Phase 4 — Analytics Layer
- Created 6+ Pivot Tables covering:
  - Revenue by Region
  - Revenue by Category & Sub-Category
  - Monthly Sales Trend (Time Series)
  - Units Sold by Segment
  - MoM & YoY Growth Calculations

### Phase 5 — Dashboard Design
- Assembled all visuals into a unified **single-sheet executive dashboard**
- Applied consistent color theming, typography, and layout hierarchy
- Added slicers for `Region` and `Category` with cross-filter synchronization

---

## 🎛️ Dashboard Features

| Feature | Implementation | Business Value |
|---|---|---|
| **Interactive Slicers** | Region & Category filters | Drill-down capability |
| **Time Series Chart** | Monthly revenue trend line | Seasonality detection |
| **Bar Charts** | Regional & category comparisons | Performance benchmarking |
| **KPI Cards** | Total Revenue, Units Sold | Executive summary view |
| **MoM Analysis** | % change table with conditional formatting | Velocity tracking |
| **YoY Analysis** | Annual comparison metrics | Strategic benchmarking |
| **Conditional Formatting** | Color-coded performance indicators | Instant visual cues |

---

## 💡 Analytical Insights

Key findings surfaced through this analysis:

- **Regional Performance:** The West region consistently outperforms other regions in total revenue, while the South shows the highest growth rate quarter-over-quarter
- **Category Intelligence:** Technology drives the highest revenue per order, while Office Supplies leads in order volume
- **Seasonality Patterns:** Q4 exhibits peak sales performance across all categories — aligned with holiday procurement cycles
- **Growth Trajectory:** YoY analysis reveals consistent upward revenue trend, validating business expansion strategies

---

## 🛠️ Skills Demonstrated

### Technical Skills
```
Excel Advanced Features    ████████████████████  Expert
Pivot Tables & Charts      ████████████████████  Expert  
Data Cleaning              ██████████████████░░  Advanced
Formula Engineering        ██████████████████░░  Advanced
Dashboard Design           █████████████████░░░  Advanced
Statistical Analysis       ████████████████░░░░  Proficient
```

### Analytical Skills
- ✅ Business KPI definition and metric design
- ✅ Time-series trend analysis (MoM, YoY)
- ✅ Segmentation and cohort analysis
- ✅ Data storytelling and executive reporting
- ✅ Root cause analysis for performance variances

### Tools & Technologies
`Microsoft Excel` · `Pivot Tables` · `Pivot Charts` · `Power Query (basic)` · `Conditional Formatting` · `Slicers` · `Data Validation` · `Advanced Formulas (SUMIF, VLOOKUP, INDEX-MATCH)`

---

## 🚀 How to Use

```bash
# Step 1: Clone the repository
git clone https://github.com/karthiikofcl07/Sales-Performance-dashboard.git

# Step 2: Open the Excel file
# → Navigate to the 'Dashboard' sheet tab

# Step 3: Interact with the dashboard
# → Use Region slicer to filter by geography
# → Use Category slicer to drill into product lines
# → Hover over charts for detailed tooltips
```

**System Requirements:** Microsoft Excel 2016 or later (Slicers and Pivot Chart features required)

---

## 📂 Dataset

| Property | Details |
|---|---|
| **Source** | [Kaggle — Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) |
| **Records** | 9,994 transactions |
| **Time Period** | 2014 – 2017 |
| **Geography** | United States (4 Regions) |
| **Categories** | Technology, Furniture, Office Supplies |
| **Fields** | 21 columns including Order ID, Sales, Profit, Quantity, Discount, Segment, Ship Mode |

---

## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karthiikofcl07)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](#)

</div>

---

<div align="center">

⭐ **If this project added value to you, consider starring the repository!** ⭐

*Built with precision and purpose — demonstrating that Excel remains a world-class BI tool when wielded with analytical rigor.*

</div>
