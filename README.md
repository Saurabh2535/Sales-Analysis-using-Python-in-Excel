# 📊 Sales Data Analysis using Python in Excel

This project is an end-to-end **Sales Analysis Dashboard** created by integrating **Python directly within Excel** using Microsoft’s new **Python in Excel** feature. The dataset includes sales transactions with details like customer, city, payment mode, quantity, and sales amount.

---

## 🔍 Objective

To perform interactive and dynamic analysis of sales data across cities and payment modes and to visualize insights using Python-powered charts directly within Excel.

---

## 📁 Dataset Overview

- Sheet Name: `Sales Data`
- Total Rows: 19,576
- Columns:
  - `Date` – Purchase date (formatted to `dd-mm-yyyy`)
  - `Customer` – Customer name
  - `City` – City of purchase (e.g., Bengaluru, Mysuru, Mangaluru, Hubli)
  - `Mode` – Payment mode (Cash / Online)
  - `Quantity` – Number of units sold
  - `Sales` – Total sales amount

---

## 🛠️ Tools & Technologies Used

- 📗 **Excel** (Python in Excel feature)
- 🐍 **Python**: `pandas`, `seaborn`, `matplotlib`
- 📊 **Interactive Visualizations** using slicers, dropdowns, and dynamic formulas

---

## 📈 Key Analytical Steps (Sheet: `Python`)

### ✅ Data Exploration
- Used `df.describe()` to summarize `Sales` and `Quantity`
- Used dropdowns to interactively analyze:
  - Total sales by `City`, `Mode`, and `Date`

### 📅 Time-Series Analysis
- Grouped by `Date` using `pd.Grouper()` and slicer options:
  - `D` – Daily
  - `W` – Weekly
  - `M` – Monthly

### 📊 KPI Metrics
- Total Sales and Quantity
- Average Order Value (AOV) by:
  - City
  - Mode of Payment

---

## 📊 Visualizations (Sheet: `Data Visualization`)

| Chart | Description |
|-------|-------------|
| **Line Plot** | Sales trend over time (based on M/W/D) |
| **Pie Chart** | Quantity distribution by City / Mode |
| **Bar Plot** | Total Sales by City / Mode |
| **Bar Plot** | AOV by City |
| **Bar Plot** | AOV by Mode |
| **Grouped Bar Chart** | Combined AOV by City and Mode using seaborn |

---

### 🧠 Learnings
-Gained hands-on experience using Python in Excel

-Built interactive dashboards without external tools

-Combined Python analytics power with Excel's flexibility

-Understood real-world sales KPIs and visual storytelling
