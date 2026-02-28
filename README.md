# Task-1--FUTURE_DS_01
Business Sales Performance Analytics

📌 Project Overview
This project analyzes one year of transaction data (December 2010 – December 2011) from a UK-based online retailer that specializes in unique all-occasion gifts. The business primarily sells to wholesalers but also serves individual customers. The goal was to clean the raw data, extract meaningful business insights, and build an interactive Excel dashboard that answers key questions: Which products generate the most revenue? How do sales trend over time? Which regions are most profitable? Where should the business focus to grow faster?

📁 Dataset
The dataset comes from Kaggle and contains approximately 541,909 transactions with 8 columns: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country. It includes both sales and cancellations (invoices starting with 'C').

🛠️ Tools Used
Microsoft Excel was used exclusively for this project. Key features include PivotTables, formulas, charts, KPI cards, and interactive slicers.

🧹 Data Cleaning Process
Raw data was copied to a working sheet where several transformations were applied: a TransactionType column was created to identify cancellations, Revenue was calculated (Quantity × UnitPrice), date components were extracted (Year, Month, Quarter, Day of Week, Hour), CustomerSegment flagged missing IDs as "Guest", Region split UK vs International, and Revenue_Band categorized transaction sizes.

📊 Analysis & Visualizations
The dashboard includes KPI cards showing Total Revenue, Total Quantity, Average Price per Unit ($1.88), Cancellation Rate (1.85% based on 9,255 cancellations), Total Orders, and Unique Customers. Visualizations include Monthly Revenue Trend, Top 20 Products by Revenue, Revenue by Day of Week, Revenue by Hour, UK vs International Revenue pie chart, and Cancellation Revenue by Month. Slicers for Month, Year, Region, and Revenue Band make the dashboard fully interactive.

🔍 Key Insights
Total Revenue reached $9,726,201 with 5162413 units sold. The United Kingdom dominates with approximately 85% of revenue, though international customers show higher average order values. Revenue peaks sharply in November, suggesting strong holiday seasonality. Top products are predominantly homeware and gift items like cake stands and decorative lights. Cancellations, while only 1.85% of transactions, cluster around specific products that may require operational review.

💡 Recommendations
Focus marketing efforts on November holiday season, investigate top cancelled products for quality issues, target high-AOV international countries like Netherlands and Ireland, develop loyalty programs for one-time buyers, and consider bundling low-margin items with best-sellers.

👤 Author
PATIENCE MABUZA
