
# 🏡 Real Estate Power BI Dashboard

This repository contains an interactive Power BI dashboard project that analyzes home sales data across New Jersey. The dashboard was created as part of a data visualization assessment and focuses on extracting actionable insights from residential property data.

## 📊 Dashboard Overview

The dashboard presents:

- **Key Metrics (KPI Cards):**
  - Average Listing Price
  - Average Selling Price
  - Total Listings
  - Total Properties Sold
  - Price Difference

- **Visualizations:**
  - 📈 **Sold Listing Trends** – Trends in monthly property sales
  - 🏙️ **Average Price by City** – Bar chart showing city-wise average selling prices
  - 🧭 **Listing vs Sold by Zip Code** – Horizontal bar chart comparing listing vs sold counts
  - 🏠 **Home Type Distribution** – Donut chart showing split between Single Family, Multi Family, and Land
  - 💲 **Listings by Price Range** – Grouped column chart by price brackets
  - 📅 **Price Trends Over Time** – Line chart comparing listing and selling price trends by month
  - 🔍 **Sold vs Unsold Distribution** – Pie chart showing sale status
  - 💰 **Top 10 Expensive Properties** – Table showing high-value listings with sale status and lot size
  - 🔘 **Interactive Filters** – City, Zip Code, and Status (Sold/Pending)

## 📁 Project Structure

```
real-estate-dashboard/
│
├── data/
│   ├── house_details.csv
│   ├── dates_price.csv
│   ├── zip_data.csv
│
├── visuals/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│
├── exports/
│   ├── Assignment.pdf
│
├── Assignment.pbix      # Main Power BI file
├── README.md            # Project description (this file)
```

## 🧼 Data Preparation Summary

- 🔍 **Fields used**:
  - `actual_sold_price`, `listing_price`, `listing_date`, `sold_date`, `status`, `acre_lot`, `city`, `state`, `zip_code`, `id`
- 🧹 **Excluded fields**:  
  - Fields like `bath`, `bed`, `play_ground`, and `swmming_tank` were left out as they did not add much value to the overall pricing or market trend analysis.
- ❌ **Records Removed**:
  - Some records were excluded due to missing values in critical fields such as price or location. A few unrealistic outliers were also filtered to avoid skewing the metrics.

## 🛠 Technologies

- **Power BI Desktop**
- **PostgreSQL (for original data transformation)**
- **Excel (data source)**

## 📎 Sample Report

See the exported PDF: [`Assignment.pdf`](./exports/Assignment.pdf)

