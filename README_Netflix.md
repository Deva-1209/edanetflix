# Netflix Userbase Exploratory Data Analysis

## Overview
This notebook performs **Exploratory Data Analysis (EDA)** on a Netflix userbase dataset. It investigates user demographics, subscription preferences, device usage, and revenue patterns through statistical summaries and a range of visualizations.

---

## Dataset
- **File:** `Netflix Userbase.csv`
- **Key Columns:** `User ID`, `Age`, `Gender`, `Country`, `Device`, `Subscription Type`, `Plan Duration`, `Monthly Revenue`

---

## Requirements
```
pandas
matplotlib
seaborn
```

---

## Workflow

### Data Inspection
- `.head()` — Preview the first few rows
- `.describe()` — Summary statistics
- `.info()` — Column types and non-null counts
- `.nunique()` — Count of unique values per column
- `.isna().sum()` — Check for missing values

### Aggregated Statistics
- Average monthly revenue by subscription type
- User count by country
- Median age by plan duration
- Total revenue by gender
- Average age by device

### Visualizations
- **Scatter plot** — Age vs. Monthly Revenue, colored by gender
- **Bar chart** — Average monthly revenue by country
- **Pairplot** — Relationship between Monthly Revenue and Age
- **Count plot** — Subscription type distribution
- **Histogram** — Monthly revenue distribution (with KDE)
- **Count plot** — Device distribution
- **Histogram** — Age distribution (with KDE)

---

## Output
A series of charts providing insight into Netflix user demographics, subscription trends, and revenue patterns across different countries, devices, and user groups.

---

## How to Run
1. Place `Netflix Userbase.csv` in the same directory as the notebook.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open and run all cells in `netfix_data.ipynb`.
