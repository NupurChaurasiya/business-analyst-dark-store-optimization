# Quick Commerce Delivery Optimization & Customer Experience Analysis

## Project Overview

This project focuses on analyzing operational performance, customer experience, and inventory efficiency for a fictional quick-commerce company called **SwiftKart**.

The objective of this project is to identify key operational bottlenecks affecting delivery performance, customer satisfaction, and inventory management using Business Analysis techniques and data visualization tools.

This project simulates a real-world business problem faced by quick-commerce companies such as Blinkit, Zepto, Instamart, and BigBasket.

---

# Business Problem

SwiftKart has recently experienced:

- Increasing delivery delays
- High cancellation rates
- Poor customer ratings
- Inventory wastage
- Peak-hour operational inefficiencies
- Stock availability issues

Management wants to understand:

- Why deliveries are getting delayed
- Which cities and dark stores are underperforming
- How traffic and weather impact delivery operations
- What factors influence customer satisfaction
- How inventory wastage can be reduced

As a Business Analyst, this project aims to analyze operational data and provide actionable business recommendations.

---

# Project Objectives

The primary objectives of this project are:

- Analyze delivery performance
- Identify causes of order cancellations
- Improve customer satisfaction
- Reduce inventory wastage
- Optimize dark store operations
- Track operational KPIs
- Recommend business improvements

---

# Dataset Information

The dataset contains 500 rows of simulated quick-commerce operational data.

## Dataset Columns

| Column Name | Description |
|---|---|
| Order ID | Unique order identifier |
| City | Order location |
| Dark Store ID | Dark store handling the order |
| Product Category | Category of ordered products |
| Delivery Time | Total delivery time in minutes |
| Traffic Level | Low / Medium / High |
| Delivery Partner Rating | Rating of delivery partner |
| Customer Rating | Customer satisfaction rating |
| Inventory Wastage % | Percentage of inventory wasted |
| Cancellation Status | Order cancelled or not |
| Stock Availability | In Stock / Low Stock / Out of Stock |
| Delivery Distance | Distance covered for delivery |
| Order Value | Total order value |
| Peak Hour | Whether order was during peak hours |
| Weather Condition | Clear / Rainy / Cloudy / Foggy |

---

# Tools Used

- Microsoft Excel
- Power BI
- Google Sheets
- Canva
- Draw.io

---

# Key Business KPIs

The following KPIs were analyzed:

| KPI | Description |
|---|---|
| Average Delivery Time | Measures delivery efficiency |
| Cancellation Rate | Tracks cancelled orders |
| Customer Satisfaction Rating | Measures customer experience |
| Inventory Wastage % | Measures operational losses |
| On-Time Delivery % | Tracks delivery performance |
| Peak Hour Delay % | Measures operational pressure during rush hours |
| Stock Availability Rate | Tracks inventory efficiency |

---

# Business Questions Answered

## Delivery Performance Analysis
- Which city has the highest delivery delays?
- Which dark stores are underperforming?
- How does traffic affect delivery time?
- How does weather impact operations?

## Customer Experience Analysis
- What factors reduce customer ratings?
- Does delayed delivery increase cancellations?
- Which cities have the highest customer dissatisfaction?

## Inventory Analysis
- Which product categories have the highest wastage?
- How does stock availability affect cancellations?
- Which stores face inventory shortages most frequently?

## Operational Efficiency Analysis
- What happens during peak hours?
- Which stores need operational improvements?
- Which delivery conditions create bottlenecks?

---

# Dashboard Overview

The Power BI dashboard includes:

## Executive Dashboard
- Total Orders
- Avg Delivery Time
- Cancellation Rate
- Avg Customer Rating
- On-Time Delivery %

## Delivery Performance Dashboard
- Delivery Time by City
- Delivery Time by Traffic Level
- Peak Hour Analysis
- Delivery Partner Performance

## Customer Experience Dashboard
- Customer Ratings Analysis
- Cancellation Analysis
- Delay vs Satisfaction Correlation

## Inventory Dashboard
- Wastage by Product Category
- Stock Availability Analysis
- Inventory Risk Areas

---

# Key Insights

Some major insights identified from the analysis:

- High traffic significantly increased delivery time
- Peak-hour operations caused major delivery delays
- Out-of-stock products increased cancellation rates
- Poor delivery experience reduced customer ratings
- Dairy and frozen food categories had the highest inventory wastage
- Certain dark stores consistently underperformed

---

# Root Cause Analysis

Root cause analysis was performed using:

- Fishbone Diagram
- 5 Whys Analysis

## Major Causes Identified

- Traffic congestion
- Inefficient route allocation
- Peak-hour staffing shortages
- Inventory mismatches
- Poor stock forecasting
- Weather-related disruptions

---

# Business Recommendations

## Operational Improvements
- Implement traffic-based route optimization
- Increase staffing during peak hours
- Improve dark store allocation strategy

## Inventory Improvements
- Improve demand forecasting
- Reduce overstocking of perishable items
- Monitor high-wastage categories closely

## Customer Experience Improvements
- Introduce proactive delay notifications
- Improve delivery partner training
- Offer compensation for delayed deliveries

## Technology Recommendations
- Use AI-based demand forecasting
- Enable real-time tracking dashboards
- Improve operational monitoring systems

---

# Expected Business Impact

If implemented, the recommendations may help achieve:

- 20% reduction in delivery delays
- 15% improvement in customer ratings
- 18% reduction in inventory wastage
- 12% reduction in cancellation rates

---

# Project Structure

```bash
quick-commerce-business-analysis/
│
├── README.md
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── dashboard/
│   ├── dashboard.pbix
│   └── screenshots/
│
├── documents/
│   ├── BRD.pdf
│   ├── KPI_Report.pdf
│   ├── Process_Flow.pdf
│   └── Final_Insights_Report.pdf
│
├── presentation/
│   └── Final_Presentation.pptx
│
└── images/
    └── dashboard_preview.png
