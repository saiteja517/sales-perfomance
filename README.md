# 📊 Sales Performance Dashboard

An Excel-based sales analytics dashboard providing pivot-table driven insights across product categories, shipping modes, regions, and time periods (2015–2018).

---

## 📁 File Structure

```
dashboard_project_1.xlsx
├── Sheet1     — Pivot tables & summary metrics
└── Sheet5     — Sales Performance Analysis
```

---

## 📌 Overview

This dashboard analyzes **9,792 orders** totalling **$2,255,621** in sales (average order value: ~$230.35).

It covers four key analytical dimensions:

| Dimension | Coverage |
|---|---|
| **Product Categories** | Furniture, Office Supplies, Technology |
| **Shipping Modes** | Standard Class, Second Class, First Class, Same Day |
| **Top States** | California, New York, Texas, Pennsylvania, Illinois |
| **Time Period** | January 2015 – December 2018 |

---

## 📂 Dashboard Sections

### 1. Sales by Sub-Category
Pivot table showing each product sub-category's share of total sales.

**Top performers:**
- Phones — 16.3%
- Chairs — 13.7%
- Binders — 10.8%

### 2. Sales by Shipping Mode
Distribution of sales across shipping methods.

| Shipping Mode | Share |
|---|---|
| Standard Class | ~59.6% |
| Second Class | ~18.7% |
| First Class | ~16.2% |
| Same Day | ~5.5% |

### 3. Average Shipping Time by Region & Mode
Pivot table showing average shipping time (in days) broken down by region (Central, East, South, West) and shipping mode.

**Overall average:** ~3.96 days

### 4. Order Count by State (Top 5)
| State | Orders |
|---|---|
| California | 1,940 |
| New York | 1,084 |
| Texas | 907 |
| Pennsylvania | 632 |
| Illinois | 563 |

### 5. Monthly Sales by Category (2015–2018)
Time-series pivot table with monthly sales broken down by Furniture, Office Supplies, and Technology — enabling trend and seasonality analysis.

**Total Sales:**
| Category | Total Sales |
|---|---|
| Technology | $847,749 |
| Office Supplies | $704,315 |
| Furniture | $703,557 |

---

## 🛠️ Tools & Requirements

- **Microsoft Excel** (2016 or later) or **Google Sheets** / **LibreOffice Calc**
- Pivot tables used throughout — refresh required if underlying data changes

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `dashboard_project_1.xlsx` in Excel.
3. Navigate between **Sheet1** and **Sheet5** using the tab bar.
4. Use slicers or filters (if present) to explore specific segments.
5. To refresh pivot tables: `Data → Refresh All`

---

## 📈 Key Insights

- **Technology** is the highest-revenue category, driven by Phones and Copiers.
- **Standard Class** shipping dominates (nearly 60% of orders).
- **California** leads in order volume — nearly double that of New York.
- Sales show a clear **year-end surge** (November–December) each year.
- **Q3 (September)** consistently records a mid-year spike across all categories.

---

## 📄 License

This project is for analytical and educational purposes. Data may be based on the Superstore sample dataset.
