# 🏡 Real Estate Dashboard – Power BI Project

This project is a real estate data analysis dashboard built using Power BI. The goal was to analyze housing data across New Jersey and visualize key insights such as price trends, home types, and sale activity.

## 📊 Dashboard Overview

The dashboard includes:

- ✅ KPIs (Total Listings, Properties Sold, Average Prices)
- 📈 Trends over time (Listings, Sold Rates)
- 🏙️ Average price by City and Zip Code
- 🏘️ Distribution by Home Type and Acreage
- 📌 Population and Zip Code Insights
- 🎯 Filters by City and Zip

### 📁 Pages:
- **Page 1**: Main metrics and high-level visualizations
- **Page 2** *(if included)*: Additional insights like average price per acre, listing price range, etc.

## 📂 Files

- `Assignment.pbix`: Power BI project file
- `data/`: Raw data files used for importing into Power BI
- `visuals/`: Screenshots of the final dashboard for preview
- `exports/assignment_report.pdf`: Exported report (if applicable)

## 🧼 Data Cleaning & Processing

- Removed rows with missing key fields like `listing_price`, `actual_sold_price`, `city`, `state`, or `zip_code`
- Focused on relevant fields:
  - ✅ Used: `actual_sold_price`, `listing_price`, `listing_date`, `sold_date`, `status`, `acre_lot`, `city`, `state`, `zip_code`
  - ❌ Skipped: less relevant or inconsistent fields like `play_ground`, `swmming_tank`, `bath`

## 📦 Technologies

- Power BI (Desktop)
- PostgreSQL (for relational data structuring)
- Excel/CSV (for raw data input)

