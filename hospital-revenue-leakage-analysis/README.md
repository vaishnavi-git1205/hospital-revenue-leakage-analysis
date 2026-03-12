# 🏥 Hospital Revenue Leakage Detection System
### End-to-End Business Analyst Portfolio Project

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Tools](https://img.shields.io/badge/Tools-Excel%20|%20SQL%20|%20Power%20BI-blue)
![Domain](https://img.shields.io/badge/Domain-Healthcare%20|%20Revenue%20Cycle-orange)
![Level](https://img.shields.io/badge/Level-Fresher%20BA%20Portfolio-purple)

---

## 📌 Project Overview

**Business Problem:**  
ABC Multi-Specialty Hospital (a simulated 300-bed hospital) is losing approximately **32% of its total billed revenue** due to high insurance claim rejection rates, billing documentation gaps, and an absence of a pending claim follow-up process.

**Role:** Business Analyst (Solo Project)  
**Data:** 500 patient billing records | Jan 2023 – Jan 2024  
**Deliverables:** Excel Workbook → SQL Analysis → Power BI Dashboard → BRD → Recommendations Report

---

## 🎯 Business Questions Answered

| # | Business Question | Tool Used |
|---|---|---|
| 1 | How much total revenue is leaking and what % is it? | SQL + Power BI |
| 2 | Which departments have the highest leakage? | SQL + Excel Pivot |
| 3 | Which insurance type rejects the most claims? | SQL + Power BI |
| 4 | WHY are claims being rejected (root cause)? | SQL |
| 5 | Is leakage getting better or worse over time? | SQL + Power BI |
| 6 | Which doctors have the highest rejection rates? | Excel Scorecard |
| 7 | Which pending claims can be recovered immediately? | SQL |
| 8 | What are the top 3 recommendations to fix this? | Recommendations Report |

---

## 🔑 Key Findings

> **Finding 1 — Department Leakage**  
> Oncology and Cardiology departments account for **52% of total revenue leakage** despite representing only 31% of patients, due to high-value billing and complex insurance requirements.

> **Finding 2 — Insurance Rejection**  
> Government insurance has a **34% rejection rate** — the highest of all 5 payer types. Root cause: Incomplete documentation (32% of all rejections).

> **Finding 3 — Pending Claims**  
> A significant backlog of Pending claims (no defined SOP) represents **immediately recoverable revenue** with a simple process fix.

---

## 💡 Recommendations & Projected Impact

| Recommendation | Expected Impact |
|---|---|
| Assign dedicated billing coordinators to Oncology & Cardiology | 18–22% leakage reduction in 60 days |
| Implement Government Insurance Documentation Checklist | Reduce rejection rate from 34% → below 12% |
| 30-day Pending Claim Follow-Up SOP | Full backlog recovery within 60 days |

---

## 🛠️ Tools & Technologies

| Tool | Purpose | Version |
|---|---|---|
| **Microsoft Excel** | Data cleaning, pivot analysis, doctor scorecard | 2019+ |
| **SQL (SQLite)** | 8 business queries for root cause analysis | DB Browser for SQLite |
| **Power BI Desktop** | 5-page interactive dashboard | Free |
| **draw.io** | Billing process flow diagram (AS-IS & TO-BE) | Web-based |
| **Microsoft Word** | BRD and Recommendations Report | 2019+ |

---

## 📁 Repository Structure

```
hospital-revenue-leakage-analysis/
│
├── 📂 01_Data/
│   ├── raw_data.csv                        ← Original 500-row dataset
│   └── Hospital_Revenue_Analysis.xlsx      ← 7-tab Excel workbook
│       ├── RAW_DATA                        ← Unmodified source data
│       ├── CLEANED_DATA                    ← Cleaned + calculated columns
│       ├── DATA_DICTIONARY                 ← Column definitions
│       ├── DATA_QUALITY_LOG                ← Issues found & fixed
│       ├── PIVOT_ANALYSIS                  ← Dept & insurance summaries
│       ├── SQL_RESULTS                     ← Query results pasted
│       └── DOCTOR_SCORECARD                ← Doctor performance table
│
├── 📂 02_SQL/
│   └── hospital_queries.sql               ← 8 business queries + bonus query
│
├── 📂 03_PowerBI/
│   ├── hospital_dashboard.pbix            ← Power BI file (build using guide)
│   ├── POWERBI_BUILD_GUIDE.md             ← Step-by-step dashboard guide
│   └── dashboard_screenshots/             ← Add screenshots after building
│
└── 📂 04_Business_Documents/
    ├── BRD_Hospital_Revenue_Leakage.docx  ← Business Requirements Document
    └── Recommendations_Report.docx        ← Findings & recommendations
```

---

## 📊 Dashboard Pages (Power BI)

| Page | Description |
|---|---|
| **Page 1 — Executive Summary** | KPI cards: Total Billed, Collected, Leakage %, Rejection Rate |
| **Page 2 — Department Analysis** | Bar chart + table of leakage by department |
| **Page 3 — Insurance Analysis** | Rejection rates by insurance type |
| **Page 4 — Monthly Trends** | Line chart of leakage over 12 months |
| **Page 5 — Recommendations** | Text-based findings & action plan |

---

## 🗺️ How to Reproduce This Project

### Step 1 — Open Excel Workbook
1. Download `01_Data/Hospital_Revenue_Analysis.xlsx`
2. Explore all 7 tabs — start with `DATA_DICTIONARY` to understand the data
3. Review `DATA_QUALITY_LOG` to see all cleaning steps documented

### Step 2 — Run SQL Queries
1. Install [DB Browser for SQLite](https://sqlitebrowser.org/) (free)
2. Create new database → Import `raw_data.csv`
3. Open `02_SQL/hospital_queries.sql` → run each query
4. Copy results back into `SQL_RESULTS` tab of Excel

### Step 3 — Build Power BI Dashboard
1. Install [Power BI Desktop](https://powerbi.microsoft.com/) (free)
2. Follow `03_PowerBI/POWERBI_BUILD_GUIDE.md` step by step
3. Connect to `Hospital_Revenue_Analysis.xlsx` as data source

### Step 4 — Review Business Documents
1. Open `BRD_Hospital_Revenue_Leakage.docx` — full requirements document
2. Open `Recommendations_Report.docx` — findings and action plan

---

## 📈 Skills Demonstrated

- ✅ **Data Collection** — Realistic dataset generation (500 rows)
- ✅ **Data Cleaning** — Duplicate checks, null handling, calculated fields
- ✅ **Documentation** — Data dictionary, data quality log
- ✅ **SQL Analysis** — 8+ business queries with CASE, GROUP BY, subqueries
- ✅ **Data Visualization** — Power BI 5-page interactive dashboard
- ✅ **Requirements Gathering** — Full BRD with stakeholders and KPIs
- ✅ **Business Communication** — Recommendations report with projected impact
- ✅ **Root Cause Analysis** — Rejection reason breakdown and prioritization
- ✅ **Process Improvement** — AS-IS vs TO-BE process flow

---

## 👤 About

**[vaishnavipalamakula]**  
Aspiring Business Analyst | Fresher  
📧 [vaishnavipalamakula@gmail.com]  

*This is a portfolio project built to demonstrate end-to-end Business Analyst skills. Data is simulated for learning purposes.*

---

## 📄 License

This project is open for educational reference. Please credit if used as inspiration.
