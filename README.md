# SQL Product Sales Analysis

A modular SQL analysis project examining product sales performance across regions, customer types, and time, turning raw transactional data into actionable business insights.

---

## Key Findings

| Metric | Value |
|---|---|
| Total Revenue | $4,379,992 |
| Total Units Sold | 15,616 |
| Peak Month | March 2023 — $208,549 |
| Lowest Month | October 2023 — $78,446 |
| Top Region | North — $967,958 (22.1%) |
| Retail vs Wholesale Split | 50.1% / 49.9% |
| Top Product by Revenue | Tablet — $684,539 |

---

## Revenue by Region

| Region | Revenue | Share |
|---|---|---|
| North | $967,958 | 22.1% |
| East | $883,634 | 20.2% |
| West | $853,479 | 19.5% |
| Central | $847,154 | 19.3% |
| South | $827,768 | 18.9% |

---

## Top 5 Products

| Product | Revenue | Units Sold |
|---|---|---|
| Tablet | $684,539 | 2,577 |
| Laptop | $684,417 | 2,408 |
| Printer | $684,387 | 2,336 |
| Monitor | $651,629 | 2,177 |
| Chair | $622,589 | 2,122 |

---

## Analysis Performed

- **Monthly Sales Performance** — Revenue trends across 2023–2024
- **Revenue by Customer Type** — Retail vs wholesale breakdown
- **Revenue by Product** — Top performing product categories
- **Revenue by Region** — Geographic sales distribution
- **Total Sales & Revenue** — Consolidated business snapshot

---

## Dataset

- **File:** `Product-Sales-Region.csv.xlsx`
- **Size:** 1,500 transactions × 7 columns
- **Fields:** Date, Region, Product, Quantity, Unit Price, Customer Type, Total Price

---

## Tools & Tech Stack

| Tool | Purpose |
|---|---|
| MySQL Workbench | Querying, aggregation, joins, grouping |
| Excel (.xlsx) | Input dataset |

---

## Project Structure

```
├── LICENSE
├── Monthly Sales Performance.sql
├── Revenue By Customer Type.sql
├── Revenue By Product Type and Sales.sql
├── Revenue By Region.sql
├── Sales Data.sql
├── Total Product Sales.sql
├── Total Revenue.sql
├── Product-Sales-Region.csv.xlsx
└── README.md
```

---
