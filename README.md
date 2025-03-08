# Samsung Mobile Sales Dashboard (Power BI)

## Overview
Designed an interactive Power BI dashboard that analyzes Samsung mobile sales from **2019-2024**. The dashboard is divided into two tabs:
1. **Global Insights**: Provides an overview of revenue, product demand, and market performance.
2. **Regional Insights**: Tracks regional sales performance and examines how **5G coverage** and **product availability** impact demand.

## Data Source & Methodology
- **Dataset Source**: Downloaded from Kaggle.
- **Columns Included**:
  - Year, Quarter, Product Model, 5G Capability, Units Sold, Revenue, Market Share, Regional 5G Coverage, 5G Subscribers, Average 5G Speed, Preference for 5G, and Region.
- **Data Processing**:
  - Cleaned and transformed dataset using **Power Query**.
  - Calculated key performance indicators (**KPIs**) using **DAX**.

## Key Features of Dashboard

### **Global Insights**
#### KPIs / Cards
- **Total Revenue**
- **Total Units Sold**
- **Average Price per Unit**
- **Average Market Share**

#### Visual Insights
- **Line Chart**: Revenue by year to identify sales patterns and seasonal trends.
  ![Revenue by Year](assets/revenue-chart.png)
- **Line Chart**: 5G preference by year to track changes in customer preference.
  ![5G Preference](assets/5g-preference.png)
- **Bar Chart**: Most purchased products to highlight top-selling models.
  ![Top Products](assets/top-products.png)
- **Donut Chart**: Revenue breakdown by region to analyze global market performance.
  ![Revenue by Region](assets/revenue-region.png)

#### Filters
- **Slicers** allow users to isolate regions and time periods of interest.
  ![Filters](assets/filters.png)

---

### **Regional Insights**
#### Visual Insights
- **Line Chart**: Revenue trends by year and region.
  ![Revenue by Region](assets/revenue-region-year.png)
- **Stacked Bar Chart**: Availability of models with 5G capability by year.
  ![5G Models](assets/5g-models-available.png)
- **Line Chart**: 5G coverage trends by year and region.
  ![5G Coverage](assets/5g-coverage.png)
- **Area Chart**: Units sold by year and region.
  ![Units Sold](assets/units-sold-region.png)

#### Filters
- **Slicers** allow users to isolate regions and time periods of interest.
  ![Regional Filters](assets/regional-filters.png)

## Business Impact
- Provided **data-driven insights** for sales strategy and market expansion.
- Helped identify **high-performing regions and product categories**.
- Enabled **trend forecasting** to optimize future sales planning.

## Tech Stack
- **Power BI Features Used**:
  - **Data Cleaning**: Power Query
  - **Calculations**: DAX (Measures & Calculated Columns)
  - **Visualization**: Power BI Reports & Dashboards

## Getting Started
1. **Upload the dataset** (if applicable).
2. **Open the `.pbix` file** in Power BI.
3. **Use slicers** to explore trends across different regions and time periods.

## How to Use
1. **Download and open the Power BI file**.
2. **Interact with slicers and filters** to analyze trends.
3. **Use visualizations to derive insights** on revenue, product demand, and market share.

---
### 📌 *Feel free to contribute or report issues!* 🚀
"""
