# Tableau Sales & Customer Dashboard

An interactive Tableau dashboard built to analyze sales performance and customer behavior across 4 years of data. Covers the complete workflow: data sourcing, preparation, visualization, and insights delivery.

Built around a structured user story simulating real stakeholder requirements from sales managers, executives, and marketing teams.

📊 [View Live Dashboard on Tableau Public](https://public.tableau.com/views/SalesCustomerDashboard_17595119079390/SalesDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) &nbsp;|&nbsp; 📁 [Tableau Workbook](tableau/)

---

## Dashboard Overview

**Dataset:** 4 years of sales data | 793 customers | 3 regions | 17 product subcategories

Two interconnected dashboards with shared filters, year selection, and cross-filtering between visuals.

---

## Sales Dashboard

**Purpose:** Overview of sales metrics and trends to analyze year-over-year performance.

**What it includes:**
- KPI Overview: total sales, profit, and quantity for current vs previous year
- Sales Trends: monthly data with highest and lowest months highlighted
- Product Subcategory Comparison: sales vs profit side by side
- Weekly Trends: weekly sales and profit compared against averages

---

## Customer Dashboard

**Purpose:** Help marketing teams understand customer data, trends, and behaviors.

**What it includes:**
- KPI Overview: total customers, sales per customer, and orders vs previous year
- Customer Trends: monthly breakdown with high and low highlights
- Order Distribution: customers segmented by number of orders
- Top 10 Customers: ranked by profit with orders, sales, profit, and last order date

---

## Interactivity and Design

- Year selector for historical analysis across all visuals
- Easy navigation between Sales and Customer dashboards
- Interactive charts act as filters
- Filter by product category, subcategory, region, state, and city

---

## Key Insights

- Regional performance highlights strong markets and underperforming areas
- Top product categories drive the majority of revenue
- Customer segmentation reveals high-value vs at-risk customer groups
- YoY KPI tracking surfaces seasonal trends and growth opportunities

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Tableau | Dashboard design and visualization |
| Excel / CSV | Data source and preparation |

---

## Project Structure

```
sales-customer-dashboard/
├── Source/
│   ├── dataset.csv              # Raw sales data
│   └── requirements.md          # Full user story and business requirements
├── tableau/
│   └── Sales_Dashboard.twbx     # Tableau workbook
├── output/
│   └── dashboard_preview.png    # Screenshot exports
└── README.md
```

---

## What I Would Add Next

- Connect to a live SQL database instead of static CSV for real-time refresh
- Add forecasting using Tableau's built-in trend models
- Expand customer segmentation with RFM scoring
- Build a third dashboard focused on regional manager view with row-level filtering

---

## Author

**Suyog Desai** - [GitHub](https://github.com/Suyog-Desai) · [LinkedIn](https://linkedin.com/in/suyog-desai) · [Portfolio](https://suyogdesai.framer.website)
