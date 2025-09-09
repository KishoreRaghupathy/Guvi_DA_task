Data Analyst Intern Project

This repository contains the solutions for the Data Analyst Intern tasks provided as part of the assignment. The project covers three tasks that demonstrate data analysis, business understanding, and reporting skills using real-world style datasets.

Task 1: Sales Data Insights

Objective: Analyze a sales dataset to extract key business insights.
Key Deliverables:

Total revenue and number of transactions.

Top performing product and source.

Distribution of payment status.

Trend of sales over time.

Visualizations including sales trend, top products, and source-based sales.

Output:
A structured Excel report with KPIs and embedded charts for management review.

Task 2: Case Study – Revenue Decline

Objective: Investigate revenue decline through structured analysis.
Approach:

Team/Product KPIs

Revenue, transactions, average order value, repeat customer rate, payment success, coupon usage, and lead-to-purchase days.

Employee-level Analysis

Simulated employee KPIs (or real if available) including revenue contribution, transactions handled, response time, and scoring based on weighted performance.

Root Cause Analysis (RCA)

Monthly trend analysis.

Correlation of revenue with failed payments, coupon usage, and direct channel transactions.

Rule-based identification of possible causes for >10% revenue drops.

Output:
CSV files, visualizations, and an Excel report summarizing team KPIs, employee scores, and RCA findings.

Task 3: Product Analytics Data Interpretation

Objective: Identify the type of database and describe data points from a business and product perspective.
Analysis:

Intro Sheet: Channel acquisition and engagement metrics (Google, Facebook, Paid Search, Direct, Influencers).

Demography Sheet: User segmentation by DAU/MAU ratio, device usage, and geographic distribution.

MOM Sheet: Month-over-month user activity and bounce rate tracking.

Insights:

Likely from a Product Analytics Database (Google Analytics, Mixpanel, or Firebase).

Google/Organic channel is strongest; Facebook traffic underperforms.

DAU/MAU ratio is very low (~0.03), signaling retention problems.

User base is mobile-first (72%) and regionally concentrated in Tamil Nadu.

July shows a spike in bounce rate, pointing to a product or campaign issue.

Conclusion:
The business is acquiring users effectively but struggles with retention. Focus should shift to retention strategies, mobile UX improvements, and regional expansion beyond the strongest market.

Tools and Libraries Used

Python (pandas, numpy, matplotlib, openpyxl)

Excel for reporting

CSV/PNG for structured outputs and visualizations

How to Run

Place the datasets (Sample Data.csv, RandomData-123.xlsx) in the data/ folder.

Run the task scripts (task1_analysis.py, task2_analysis.py, task3_analysis.py).

Outputs will be saved in the outputs/ folder with Excel reports, CSVs, and charts.
