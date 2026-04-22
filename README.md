# Online Retail Sales Analysis & Interactive Dashboard

## Project Overview
This project provides a comprehensive analysis of business sales data for an international online retail store. Using a dataset of approximately 12,000 transactions (Dec 2010), I performed data cleaning, feature engineering, and visualization to answer key business questions regarding revenue growth, product performance, and regional sales trends.

## Key Business Questions Answered
* **Revenue Trends:** What are the peak shopping hours for the business?
* **Product Performance:** Which categories (Home Decor, Kitchenware, etc.) generate the most revenue?
* **Regional Analysis:** Which international markets are driving the highest sales volume?
* **Strategic Growth:** Where should the business focus its marketing efforts to maximize ROI?

## Tools Used
* **Excel:** Data cleaning, handling missing values, and advanced categorization using `IFS` and `SEARCH` functions.
* **Tableau:** Building an interactive, cross-filtered dashboard for executive reporting.
* **Python (Pandas):** Used for initial data profiling and keyword extraction to build the product taxonomy.

## Project Structure
* `FUTURE_DS_01.xlsx`: The cleaned dataset including calculated fields for Revenue, Hours, and Product Categories.
* `FUTURE_DS_01.twb`: The Tableau Workbook containing the interactive dashboard.
* `analysis_report.pdf`: (Optional) A summary of business recommendations based on the data findings.

## Data Cleaning Process
To ensure the accuracy of the analysis, the following steps were taken:
1. **Filtering:** Removed transactions with negative quantities (returns) and zero unit prices.
2. **Missing Data:** Handled missing `CustomerID` fields by labeling them as "Guest" to preserve total revenue data.
3. **Feature Engineering:** - Created a `Total Revenue` column (`Quantity` * `UnitPrice`).
   - Extracted `Hours` from the timestamp to identify peak traffic periods.
   - Built a custom **Product Categorization** logic to group 12,000+ rows into 7 distinct business segments (e.g., Seasonal, Kitchenware, Home Decor).

## Key Insights
* **Peak Traffic:** Sales significantly peak between **10:00 AM and 12:00 PM**, suggesting this is the optimal window for launching flash sales or promotional emails.
* **Dominant Category:** **Home Decor** (including items with "Heart" and "Vintage" keywords) is a primary revenue driver, accounting for a significant portion of daily sales.
* **Market Expansion:** While the UK is the primary market, **Norway and France** show high average order values, indicating strong potential for international expansion.
