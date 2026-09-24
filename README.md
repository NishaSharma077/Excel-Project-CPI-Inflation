# 📊 India CPI Inflation Analysis & Dynamic Excel Dashboard (2013–2023)

An interactive, data-driven Excel case study analyzing India's Consumer Price Index (CPI) trends, sector-wise inflation gaps (Rural vs. Urban), and commodity price volatility over a 10-year period (2013–2023).

---

## 📌 Project Overview

Inflation impacts consumer purchasing power, economic policy, and market dynamics. This project transforms raw CPI dataset records into an executive-ready Excel dashboard featuring interactive slicers, cross-filtering charts, dynamic Pivot Tables, and core KPI metrics.

### Key Objectives:
* **Track Macro Trends:** Analyze overall national inflation trajectory from 2013 to 2023.
* **Sectoral Disparity:** Measure rural vs. urban CPI inflation gaps.
* **Basket Analysis:** Identify price volatility across key commodity groups (Food & Beverages, Fuel, Housing, Clothing, Spices, etc.).
* **Interactive Visualization:** Build a dynamic dashboard utilizing Excel Pivot Tables, Slicers, and linked Pivot Charts.

---

## 📈 Key Dashboard Metrics (KPIs)

* **Current CPI Index (2023):** `177.62`
* **10-Year Cumulative Inflation:** `+61.4%` *(2013 to 2023)*
* **YoY Inflation Rate:** `+3.18%` *(2023 vs. 2022)*
* **Rural vs. Urban Inflation Gap:** `+1.86` higher in rural sectors
* **Most Volatile Category:** `Meat and Fish` (Std Dev: 33.35)
* **Most Stable Category:** `Sugar and Confectionery` (2023 Avg Index: 121.02)

---

## 🛠️ Data & Excel Features Used

* **Pivot Tables & Shared Pivot Caches:** Built connected Pivot Tables across multiple analysis sheets to enable multi-chart slicing.
* **Dynamic Slicers:** Connected `Year` and `Sector` slicers linked via Report Connections to update all dashboard charts simultaneously.
* **Excel Formulas:** Implemented `AVERAGEIFS`, `MAXIFS`, `STDEV.S`, and percentage change formulas for real-time KPI card tracking.
* **Advanced Visuals:**
  * 3D Pie & Donut Charts for Category Basket Share
  * Multi-line trend charts for YoY inflation trajectories
  * Formatted KPI Cards for executive summary insights

---

## 📂 Repository Structure

```text
├── CPI Case Study.xlsx           # Main Excel workbook with Data, Pivot Tables & Dashboard
├── CPI Inflation.xlsx            # Source dataset sheet
├── screenshots/                  # Preview images of dashboard layout & slicer connections
└── README.md                     # Project documentation
