# Adidas Sales Analysis Dashboard

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/20/Adidas_Logo.svg" alt="Adidas Logo" width="150"/>
</p>

This project presents a dynamic Tableau dashboard that analyzes Adidas sales data across products, regions, retailers, sales channels, and time. It aims to help stakeholders uncover actionable insights into business performance and customer behavior.

**Live Dashboard**: [View on Tableau Public](https://public.tableau.com/views/AdidasSalesAnalysis_17478451254390/DashboardOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
**Dataset**: [Adidas Sales Dataset on Kaggle](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset)

---

## Table of Contents

- [Overview Dashboard](#-overview-dashboard)  
- [Details Dashboard](#-details-dashboard)  
- [Filters](#-filters)
- [Tools Used](#-tools-used)

---

## Overview Dashboard
<img width="650" height="330" alt="Screenshot 2025-05-21 194003" src="https://github.com/user-attachments/assets/da2edd45-10c2-4929-a093-aff829d71906" />

This page summarizes the overall business performance with interactive visualizations across multiple dimensions.

### Profit by Total Sales (Scatterplot)
- Shows a strong positive correlation between total sales and profit.
- Useful to spot top-performing products and retailer-product combos.

### Units Sold by Product (Treemap)
- **Men’s Street Footwear** sold the most (593K units).
- Apparel categories underperform in volume, suggesting areas for growth.

### Key Metrics
- **Total Sales**: `$900M`  
- **Total Units Sold**: `2.5M`

### % Orders by Sales Method (Donut Chart)
- **Online** orders lead with **51%**, followed by **Outlet** (31%) and **In-store** (18%).
- Reflects customer preference for digital channels.

### Total Sales by Date (Area Chart)
- Clear growth in late 2020 through 2021.
- Seasonal or promotional trends may explain peaks.

### Profit by Retailer (Bar Chart)
- **West Gear** is the top contributor with **$86M** in profit.
- **Walmart** and **Amazon** show the lowest profit margins.

---

## Details Dashboard
<img width="650" height="330" alt="Screenshot 2025-05-23 160008" src="https://github.com/user-attachments/assets/d94b13cc-2eb1-4c0d-bdee-d39c9ed60330" />

This section drills into geographic and order-level details.

### Total Sales by State (Map)
- Top states: **New York, California, Florida**.
- Highlights where Adidas products perform best.

### Top 5 States by Total Sales (Bar Chart)
- **New York** leads at **$64M**, followed by **California** and **Florida**.
- South Carolina appears as a fast-growing market.

### Key Metrics
- **Total Orders**: `9,648`  
- **Average Price per Unit**: `$45`  
- **Average Margin**: `42.3%`  
- **Average Profit per Order**: `$34K`

### # Orders by Region (Bar Chart)
- **West** and **Northeast** regions have the highest order volume.
- **Southeast** has the fewest—opportunity for growth.

### Total Sales and Profit by Date (Bar + Line Chart)
- Visualizes both revenue and profit trends monthly.
- Profit follows sales closely, though margins fluctuate over time.

---

## Filters

Both dashboards support dynamic filtering for custom views.

### Overview Dashboard Filters:
- `Retailer`
- `Product`
- `Year`

### Details Dashboard Filters:
- `State`
- `Sales Method`

---

## 🛠️ Tools Used

- [Tableau Public](https://public.tableau.com/) – for dashboard creation and publishing  
- Microsoft Excel / CSV – for preprocessing the dataset  
- Design aligned with **Adidas branding** – consistent colors, icons, and imagery
