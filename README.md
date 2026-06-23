# 🛒 Superstore Sales Analysis — Excel Dashboard & Pivot Analysis

## 📌 Project Overview

An end-to-end sales analysis of a Canadian Superstore's transaction data using **Microsoft Excel**. The project uncovers profitability patterns across product categories, customer segments, and regions — delivering actionable recommendations for revenue optimization.

This was completed as part of the **PwC Academy Business Analytics & Consulting Program (UpGrad)**.

---

## 🎯 Business Objective

Identify which product categories, customer segments, and regions are driving profits — and which are bleeding losses — to help the business prioritize its sales and inventory strategy.

---

## 🗂️ Dataset

| Detail | Info |
|---|---|
| Records | 8,399 transactions |
| Period | 2009 – 2012 |
| Geography | Canada (7 regions) |
| Columns | 18 fields |

**Key Fields:** Order ID, Sales, Profit, Discount, Ship Mode, Customer Segment, Product Category, Product Sub-Category, Region, Province

---

## 🛠️ Tools & Techniques Used

- **Microsoft Excel** — PivotTables, PivotCharts, Slicers
- **Conditional Formatting** — highlighting loss-making categories
- **Data Segmentation** — filtered sheets by Customer Segment
- **Profit & Loss Analysis** — category-wise and region-wise breakdowns

---

## 📊 Analysis Performed

### 1. High Profit Categories (PivotTable)
Identified top-performing product sub-categories by region:
- **Office Machines** — highest profit contributor across Prairie ($91,913) and Ontario ($28,131)
- **Binders and Binder Accessories** — strong performer in West ($43,848) and Ontario ($30,614)
- **Telephones & Communication** — consistent profit across all 7 regions

### 2. Loss Making Categories (PivotTable)
Flagged sub-categories draining profitability:
- **Tables** — biggest loss maker at **-$35,430** (Ontario worst at -$16,168)
- **Bookcases** — net loss of **-$9,305** (Quebec: -$11,366)
- **Scissors, Rulers & Trimmers** — loss of -$3,330 across most regions

### 3. Customer Segment Analysis (Separate Sheets)
Analyzed behavior across 4 segments:
| Segment | Key Insight |
|---|---|
| **Corporate** | High-value orders; Technology drives revenue |
| **Consumer** | Highest volume; mix of profitable & loss orders |
| **Home Office** | Niche but consistent; Office Supplies dominant |
| **Small Business** | High discount sensitivity; margin pressure |

---

## 💡 Key Findings & Recommendations

| # | Finding | Recommendation |
|---|---|---|
| 1 | **Tables category** loses $35K across all regions | Review pricing strategy or discontinue in loss-heavy regions |
| 2 | **Prairie region** generates highest overall profit ($132K) | Increase inventory & marketing investment in Prairie |
| 3 | **Office Machines** is the star sub-category | Prioritize stocking and promotions for Office Machines |
| 4 | **Copiers & Fax** profitable in 5/7 regions but loses heavily in Atlantic | Targeted Atlantic pricing review needed |
| 5 | **Corporate segment** has highest average order value | Offer loyalty/bulk-order deals to retain Corporate customers |

---

## 📁 Repository Structure

```
superstore-sales-analysis/
│
├── superstore_sales_data.csv         # Raw transaction data (8,399 rows)
├── superstore_sales_solution.xlsx    # Excel workbook with PivotTables & analysis
└── README.md                         # Project documentation (this file)
```

---

## ▶️ How to Explore

1. Open `superstore_sales_solution.xlsx` in Microsoft Excel
2. Navigate through the sheets:
   - **High Profit Categories** — PivotTable of profitable sub-categories by region
   - **Loss Making Categories** — PivotTable of loss-making sub-categories by region
   - **Corporate / Consumer / Home Office / Small Business** — Segment-wise filtered data
3. Use the raw data in `superstore_sales_data.csv` to build your own PivotTables

---

## 🧠 Skills Demonstrated

- PivotTable design for multi-dimensional analysis (region × sub-category)
- Business-driven data segmentation by customer type
- Profit/loss identification and root cause framing
- Clean Excel workbook structuring for stakeholder readability

---

## 👤 Author

**Jebaz Jeeva M**  
PGDM — Business Analytics & Marketing | Rajalakshmi School of Business  
[LinkedIn](https://www.linkedin.com/in/jebazjeeva/) | [GitHub](https://github.com/JebazJeeva)
