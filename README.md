# Online Retail Sales Analysis & Interactive Tableau Dashboard

## Project Overview
This project involves a comprehensive data analysis of an E-commerce dataset (approx. 12,000 transactions). The goal was to transform raw sales data into actionable business intelligence to help a retail company understand its revenue drivers, customer behavior, and geographic strengths.

## Business Key Performance Indicators (KPIs)
Based on the analysis of the processed data:
* **Total Revenue:** $210,013.27
* **Total Units Sold:** 89,578
* **Top Market:** United Kingdom ($194,007 in revenue)
* **Lead Category:** Home Decor ($44,767 in revenue)

## Tech Stack
* **Excel:** Data cleaning, missing value treatment, and product categorization using advanced logical formulas.
* **Tableau:** Developed a multi-sheet interactive dashboard (`FUTURE_DS_01.twb`) for visual storytelling.

## Repository Contents
* `Clean Online sales data.xlsx`: The finalized dataset featuring engineered columns for **Revenue**, **Hour**, and **Product Category**.
* `FUTURE_DS_01.twb`: Tableau Workbook containing the interactive dashboard.

## Data Transformation Logic
To categorize the 11,000+ items accurately, a custom keyword-matching algorithm was applied in Excel:
* **Seasonal:** Identified via keywords like "Christmas", "Tree", "Star".
* **Kitchenware:** Items like "Cake", "Mug", "Tea", "Bottle".
* **Home Decor:** Captured via "Heart", "Vintage", "Holder", "Light".
* **Bags & Travel:** Including "Jumbo Bag", "Lunch Bag", and "Totes".

## Strategic Insights & Recommendations
1. **Optimize Peak Hours:** Data shows a significant revenue surge between **10:00 AM and 11:00 AM** (peaking at over $28,000 in an hour). 
   - *Recommendation:* Schedule high-impact marketing campaigns for 9:45 AM to capture active buyers.
2. **Category Growth:** **Kitchenware** and **Home Decor** are the core pillars of the business.
   - *Recommendation:* Consider bundling top-selling Home Decor items with Kitchenware sets to increase the Average Order Value (AOV).
3. **International Potential:** Outside the UK, **Germany and EIRE** are the most consistent markets. 
   - *Recommendation:* Localized marketing and reduced shipping tiers for these two regions could drive immediate growth.
