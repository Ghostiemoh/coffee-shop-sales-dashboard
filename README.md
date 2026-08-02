# Coffee Shop Sales Dashboard ☕

An interactive Excel sales dashboard that consolidates transaction data across multiple retail coffee shop outlets. The project maps sales volume by store location, product category, and purchase hour to identify high-performance windows and product placement opportunities.

---

## 📌 Project Overview

This dashboard processes retail transactions for a multi-location coffee brand. By mapping when and where items are purchased, it exposes inventory opportunities and staff scheduling alignment windows.

### Core Insights
- **Hourly Purchase Spikes**: Sales peak dramatically between 7:30 AM and 9:30 AM (morning rush) and show a secondary light surge around 3:00 PM.
- **Product Category Mix**: Brewed coffee and espresso beverages account for 65% of overall sales volume, while bakery items show low attach rates, presenting a cross-selling opportunity.
- **Location Comparison**: The Downtown store location leads in gross revenue, while the Suburban outlet shows a higher average transaction value per basket.

---

## 🛠️ Dashboard Architecture

- **PivotTable Engine**: Groups transactional timestamps into hourly brackets and aggregates product unit sales.
- **Slicers**: Allows interactive dashboard drill-downs by:
  - Store Location
  - Product Category
  - Day of the Week

---

## 📂 File Inventory

* **`coffee-shop-sales.xlsx`**: The spreadsheet containing the transaction registry, PivotTable aggregations, and the dashboard tab.

---

## 🚀 How to Open and Use
1. Download the [`coffee-shop-sales.xlsx`](./coffee-shop-sales.xlsx) workbook from this repository.
2. Open in **Microsoft Excel**.
3. Use the slicers to segment the sales charts by store and product lines.
