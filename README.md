# 📊 Sales Analytics & Performance Executive Dashboard

[![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-2013%2B-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel)
[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Data Integrity](https://img.shields.io/badge/Data_Integrity-100%25_Verified-success?style=for-the-badge&logo=checkmarx)](tests/)
[![Automated Tests](https://img.shields.io/badge/Tests-Passing_7%2F7-brightgreen?style=for-the-badge&logo=pytest)](tests/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

> A modern, interactive multi-view **Microsoft Excel Sales Analytics Dashboard** powered by dynamic pivot tables, slicers, timelines, and shape-based app navigation. Accompanied by an automated **Python data analytics engine**, **data validation test suite**, and **clean CSV exports** for seamless business intelligence reporting.

---

## 📌 Executive Summary

This project delivers an end-to-end sales performance intelligence system designed to help executive leadership, sales directors, and regional managers monitor revenue trends, evaluate salesperson productivity, identify high-margin product categories, and optimize geographical distribution.

The system features:
- **Interactive Multi-Tab Dashboard Application**: Built inside Microsoft Excel with custom shape-based tab navigation acting like a native desktop app.
- **Dynamic Pivot Table Engine**: 12 dedicated Pivot Tables dynamically computing metrics across date, place, product, and sales rep dimensions.
- **Slicers & Interactive Timelines**: One-click filtering by time horizon, sales representative, product category, and regional market.
- **Automated Python Analytics Pipeline**: Python script (`analyze_sales.py`) to parse, audit, and generate terminal reports with zero external dependencies.
- **Automated Data Quality & Unit Tests**: Full test suite (`tests/test_dashboard_data.py`) validating formula calculations, boundary checks, and referential integrity.
- **Standardized Data Exports**: Exported CSV datasets ready for Power BI, Tableau, SQL, or machine learning pipelines.

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Value | Business Context |
| :--- | :--- | :--- |
| **Total Revenue** | **₹118,731,893.00** | Gross sales across all product lines and regions (2020–2022) |
| **Total Units Sold** | **7,670 units** | Cumulative volume across all fulfilled orders |
| **Total Transactions** | **278 orders** | Normalized transaction-level records |
| **Average Order Value (AOV)** | **₹427,093.14** | High-ticket average reflecting enterprise electronics & consumer goods |
| **Active Sales Representatives** | **6 Representatives** | Ganesh, Gopi, Kiran, Mahesh, Ramesh, Prathap |
| **Product Categories** | **6 Categories** | Laptops, 4K LED TVs, Mobiles, Furniture, Speakers, LED TVs |
| **Geographic Markets** | **6 Regions** | Tenali, Guntur, Chirala, Bapatla, Vijayawada, Ongole |
| **Reporting Horizon** | **3 Full Years** | January 1, 2020 – December 30, 2022 |

---

## 🖥️ Interactive Dashboard Showcase

The workbook features 4 specialized views interconnected by an intuitive top navigation bar:

```
  ┌─────────────────────────────────────────────────────────────────┐
  │   [ DASH BOARD ]   │   [ PRODUCTS ]   │   [ SALESMANS ]   │   [ ABOUT ]   │
  └─────────────────────────────────────────────────────────────────┘
```

---

### 1. Executive Sales Dashboard (`Dash Board`)
*High-level overview displaying enterprise KPIs, monthly sales trends, geographic distribution, and category sales mix with interactive timeline controls.*

![Executive Sales Dashboard](Dashboard%20Screenshot.png)

**Key Highlights:**
- **KPI Summary Cards**: Real-time total revenue and order volume counters.
- **Monthly Sales Trend Chart**: Line/bar visualizations charting sales trajectory across 36 months.
- **Geographical Breakdown**: Horizontal bar chart identifying regional sales contributions.
- **Category Sales**: Distribution of revenue across key consumer product lines.
- **Interactive Slicers & Timelines**: Instant date-range filtering.

---

### 2. Sales Representative Performance (`Salesmans`)
*Granular salesperson analytics designed for sales managers to track individual targets, reward top performers, and identify reps needing coaching.*

![Sales Representative Performance](Salesmans%20Screenshot.png)

**Key Highlights:**
- **Overall Performance Chart**: Comparative sales output across all 6 representatives.
- **Top 3 Sales Reps**: Dedicated leaderboard highlighting the top revenue generators (Ganesh, Gopi, Kiran).
- **Bottom 3 Sales Reps**: Focused view highlighting areas for sales pipeline improvement.
- **Representative Slicer**: Filter by individual salesperson to see filtered results instantly.

---

### 3. Product Performance Analytics (`Products`)
*Product category analytics tracking volume, revenue, and product velocity to optimize inventory and supplier procurement.*

![Product Performance Dashboard](Product%20Screenshot.png)

**Key Highlights:**
- **Volume by Quantity**: Analysis of total units sold per product category.
- **Top 3 Selling Products**: Revenue and volume leaders (Laptops, 4K LED TVs, Mobiles).
- **Bottom 3 Products**: Long-tail product performance (Furniture, Speakers, LED TVs).
- **Product Slicer & Date Timeline**: Filter product performance by quarter or year.

---

### 4. About & System Architecture (`About`)
*Project metadata, user guide, and architectural documentation embedded directly into the workbook.*

![About & Documentation](About%20Screenshot.png)

---

## 💡 Strategic Business Insights

```
                   REVENUE BY PRODUCT CATEGORY
  Laptops        ████████████████████ 41.0% (₹48.71M)
  4K LED TV's    ███████████████████▍ 39.4% (₹46.83M)
  Mobiles        ████▍                8.8%  (₹10.41M)
  Furniture      ██▏                  4.4%  (₹5.26M)
  Speakers       █▋                   3.4%  (₹3.99M)
  LED TV's       █▌                   3.0%  (₹3.52M)
```

1. **The 80/20 Power Law in Product Portfolio**:
   - **Laptops** (₹48.71M / 41.0%) and **4K LED TVs** (₹46.83M / 39.4%) together generate **80.47% of total company revenue** (₹95.54M).
   - *Recommendation*: Prioritize stock availability, OEM partnerships, and promotional bundles for laptops and premium 4K TVs.

2. **Sales Rep Productivity Concentration**:
   - **Ganesh** is the standout top performer, generating **₹40.88M (34.4%)** across 67 transactions.
   - The top 3 reps (**Ganesh, Gopi, Kiran**) account for **75.7% of all sales**.
   - *Recommendation*: Study Ganesh's sales methodology and pair underperforming reps (e.g., Prathap at ₹4.17M) with senior mentors for cross-training.

3. **Regional Market Hotspots**:
   - **Tenali** is the dominant sales hub, accounting for **₹41.05M (34.6%)** of total revenue.
   - Guntur (₹19.18M / 16.2%) and Chirala (₹16.93M / 14.3%) follow as strong tier-2 distribution hubs.
   - *Recommendation*: Establish a localized logistics and fulfillment center in Tenali to cut order turnaround time.

4. **Year-over-Year Trajectory**:
   - **2020** was an exceptional peak year (₹51.73M / 43.6%), likely driven by work-from-home electronic equipment demand.
   - **2021** (₹34.18M) and **2022** (₹32.82M) have stabilized into a steady run-rate of ~₹33M–₹34M annually.

---

## 🏗️ Technical Architecture

### Workbook Sheet Breakdown

| Sheet Name | Role | Contents & Functionality |
| :--- | :--- | :--- |
| **`Dash Board`** | Executive UI | KPI scorecards, Monthly Trend Chart, Regional Sales, Product Breakdown, Timelines & Slicers |
| **`Salesmans`** | Sales Rep UI | Sales Leaderboard, Top 3 Sales Reps, Bottom 3 Sales Reps, Slicer & Timeline |
| **`Products`** | Product UI | Units Sold by Product, Top 3 Products, Bottom 3 Products, Product Slicers |
| **`About`** | Documentation UI | Executive description, navigation guide, business objectives |
| **`Master Data`** | Data Warehouse | 278 normalized transactions with calculated `Amount = Price * Units` |
| **`Pivot Tables`** | Calculation Engine | 12 hidden Pivot Tables powering all 18 dashboard charts and cards |
| **`Sheet4` / `Sheet5`** | Scratch / Helper | Reserved auxiliary sheets |

### Pivot Table Calculation Engine

The dashboard relies on 12 optimized pivot tables situated in the `Pivot Tables` worksheet:
- **`PivotTable1`** (`A1:B3`): Sales Amount aggregated by Month and Date.
- **`PivotTable2`** (`A21:B23`): Sales Amount aggregated by Regional Place.
- **`PivotTable3`** (`A38:B40`): Sales Amount aggregated by Product.
- **`PivotTable4`** (`A53:A54`): Global Total Sales Amount KPI scorecard value.
- **`PivotTable5`** (`A61:A62`): Global Total Transaction Count KPI scorecard value.
- **`PivotTable7`–`PivotTable10`**: Product unit sales rankings and Top/Bottom filters.
- **`PivotTable11`–`PivotTable14`**: Sales representative performance rankings and Top/Bottom filters.

---

## 📋 Data Dictionary (`Master Data`)

| Field Name | Type | Constraints | Description | Example |
| :--- | :--- | :--- | :--- | :--- |
| **`Date`** | Date / Time | `2020-01-01` to `2022-12-30` | Transaction date | `2020-01-01` |
| **`Sales Persons`** | String | 6 Unique Names | Name of the assigned sales representative | `Ganesh` |
| **`Products`** | String | 6 Categories | Product category sold | `Laptops` |
| **`Place`** | String | 6 Regions | Location / City of the sale | `Tenali` |
| **`Price`** | Numeric (INR) | `> 0` | Unit selling price | `₹33,000` |
| **`Units`** | Integer | `> 0` | Number of units ordered | `26` |
| **`Amount`** | Numeric (INR) | `= Price * Units` | Total order revenue (calculated column) | `₹858,000` |

---

## 🐍 Python Analytics Engine & CLI

A lightweight, automated Python script is included to inspect, audit, and analyze the dataset from the terminal without opening Microsoft Excel.

### Running the Analytics Report

```bash
python analyze_sales.py
```

### Sample Output

```text
========================================================================
               SALES EXCEL DASHBOARD - ANALYTICS REPORT                 
========================================================================
  Reporting Period     : 2020-01-01 to 2022-12-30
  Total Revenue        : Rs 118,731,893.00
  Total Units Sold     : 7,670 units
  Total Transactions   : 278
  Average Order Value  : Rs 427,093.14
------------------------------------------------------------------------
  Data Integrity Status: 100% HEALTHY (0 errors found across all rows)
========================================================================

[+] SALES REPRESENTATIVE PERFORMANCE LEADERBOARD
Sales Person    | Total Sales      | Units    | Orders  | Share % 
-----------------------------------------------------------------
Ganesh          | Rs 40,881,900.00 | 1687     | 67      |  34.43%
Gopi            | Rs 26,744,959.00 | 1534     | 54      |  22.53%
Kiran           | Rs 22,262,435.00 | 1407     | 52      |  18.75%
Mahesh          | Rs 15,265,496.00 | 810      | 31      |  12.86%
Ramesh          | Rs 9,404,360.00  | 947      | 31      |   7.92%
Prathap         | Rs 4,172,743.00  | 1285     | 43      |   3.51%
...
```

---

## 🧪 Automated Testing & Data Quality

The project includes an automated test suite verifying data integrity, formula precision, and dimensional integrity using Python's standard `unittest` framework.

### Running Tests

```bash
python -m unittest discover -s tests -v
```

### Verified Test Cases

- `test_workbook_sheets_exist`: Confirms all 6 critical sheets (`About`, `Salesmans`, `Master Data`, `Products`, `Dash Board`, `Pivot Tables`) are intact.
- `test_master_data_row_count`: Verifies exact record count (278 transactions).
- `test_formula_amount_equals_price_times_units`: Validates `Amount == Price * Units` for 100% of rows.
- `test_no_null_values_in_master_data`: Confirms zero missing or corrupted values.
- `test_date_range_validity`: Validates all transactions occur between 2020 and 2022.
- `test_positive_pricing_and_volume`: Asserts non-negative and non-zero values for financial quantities.
- `test_csv_export_sync`: Ensures CSV exports in `data/` match Excel totals to the penny.

---

## 📁 Repository Structure

```
Sales-Execl-Dashboard/
│
├── sales Excel Dash Board.xlsx        # Main Interactive Excel Dashboard
├── analyze_sales.py                   # Automated Python CLI analytics & audit tool
├── README.md                          # Comprehensive project documentation
├── .gitignore                         # Standard git ignore rules (IDE, Excel temp, caches)
│
├── Dashboard Screenshot.png           # Screenshot of Executive Dashboard view
├── Salesmans Screenshot.png           # Screenshot of Sales Representative view
├── Product Screenshot.png             # Screenshot of Product Performance view
├── About Screenshot.png               # Screenshot of About & Navigation view
│
├── data/                              # Clean exported datasets for external BI/ML
│   ├── sales_master_data.csv          # Normalized 278-row transaction table
│   ├── summary_by_salesperson.csv     # Performance summary aggregated by rep
│   ├── summary_by_product.csv         # Performance summary aggregated by product
│   ├── summary_by_region.csv          # Performance summary aggregated by region
│   └── summary_by_monthly_trend.csv   # Aggregated monthly timeline trends
│
└── tests/                             # Quality assurance & verification suite
    └── test_dashboard_data.py         # Automated unit test suite (7/7 passing)
```

---

## 🚀 How to Use

### Option A: Using Microsoft Excel (Interactive UI)
1. Double-click to open [`sales Excel Dash Board.xlsx`](sales%20Excel%20Dash%20Board.xlsx) in **Microsoft Excel 2013 or later**.
2. If prompted, click **"Enable Editing"** and **"Enable Content"**.
3. Use the top navigation buttons (**DASH BOARD**, **PRODUCTS**, **SALESMANS**, **ABOUT**) to switch views seamlessly.
4. Click on any **Slicer** (e.g., Sales Person, Product) or **Timeline** (Months/Years) to filter data dynamically.

### Option B: Using Python CLI
1. Ensure Python 3.8+ is installed:
   ```bash
   python --version
   ```
2. (Optional) Install `openpyxl` if reading directly from `.xlsx`:
   ```bash
   pip install openpyxl
   ```
3. Run the analytical report:
   ```bash
   python analyze_sales.py
   ```
4. Run the automated data integrity test suite:
   ```bash
   python -m unittest discover -s tests -v
   ```

---

## 👤 Author & Credits

- **Creator**: [Dinesh A](https://github.com/Dinesh1535)
- **Repository**: [Sales-Execl-Dashboard](https://github.com/Dinesh1535/Sales-Execl-Dashboard)
- **Tooling**: Microsoft Excel, Python 3.10, openpyxl, GitHub Flavored Markdown

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - feel free to adapt, extend, and use it for your own business analytics projects.
