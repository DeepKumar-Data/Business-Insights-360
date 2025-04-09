Business Insights 360
A comprehensive dashboard that gives executives a real-time, 360-degree view of company
performance.

Company Overview:
ATLIQ Hardware is one of the fastest-growing electronics manufacturers, producing products such as PCs, mice, printers, desktops and other electronics related products.
Initially, the company operated in only one or two countries, which made business operations relatively simple. However, as the company expanded globally, its operations became significantly more complex. 
With expansion came challenges like managing multiple markets, customer segments, product lines, and distribution channels. This made it increasingly difficult to rely on traditional decision-making methods.”

Problem Statement: 
The company struggled with siloed data across departments, leading to delayed executive decision-making, poor inventory forecasting, and opaque regional P&L visibility.

Objectives:
1. Single Source of Truth-
The company needed one centralized and reliable platform where all important business metrics could be viewed consistently.
2. Self-Service Analytics-
Instead of depending on technical teams every time they needed a report, business users should be able to explore insights on their own.
3. Dynamic Monitoring-
The dashboard should allow real-time or near-real-time tracking of business performance, enabling faster and more informed decisions. 

End-to-End How It Works:
MySQL DB Extraction → Power Query Transformation → Data Modeling (Star Schema) → DAX KPI Creation → Power BI Report UI → Executive Publishing.

Tools & Technologies Used:
1. MySQL: Data staging.
2. Power Query: ETL processing.
3. Power BI: Visualization & Data Modeling.
4. DAX: KPI calculations (YTD, QTD, Net Sales).
5. Excel: Initial data prototyping.

Dataset Explanation: 
Fact tables: fact_sales_monthly, fact_forecast. 
Dimension: tables: dim_customer, dim_product. Contains over 1M+ rows of transactional data.

Dashboard Features:

1. Clean, interactive visuals for quick decision-making.
2. Dynamic filters and slicers for personalized views.
3. KPI Cards & Trend Charts for performance tracking.
4. Filter Panel Toggle: A collapsible filter pane activated via a Filter Button.
5. Responsive Visuals: Charts and visuals update in real-time based on filter selections. 
6. Drill-throughs & Bookmarks: Easily navigate between views and insights.
7. elected Filters Counter: Filter button dynamically updates to show the number of applied filters.