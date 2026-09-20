# SaaS-FinTech-Order-Funnel-Analysis-Uncovering-Drop-offs-and-Revenue-Opportunities
Executive Summary

Order conversion rates at our SaaS FinTech company remain below expectations. To identify root causes and quantify improvement opportunities, we extracted and analyzed order-status data using SQL, Python, and Power BI, then built a dashboard to monitor progression through the funnel.
The largest revenue opportunities lie in raising user interaction rates and completed bank-login attempts. We therefore recommend three targeted product and process changes: refined workflow copy, reminder emails/texts, and stronger client engagement. These adjustments are projected to lift conversion and daily revenue while reducing ad-hoc analytics requests.
Business Problem

Completed orders drive revenue. Product and sales stakeholders have observed that the conversion rate—from order initiation to completion—is lower than expected. The key questions are: Where are users dropping out of the workflow, and what product or process changes will most effectively encourage completion?
Methodology

SQL queries (CTEs, joins, CASE statements, and aggregations) to extract, clean, and transform order data from the database.
Power BI dashboard to track order volumes by status, overall and by client.
Python-based funnel simulation (Pandas, NumPy, Matplotlib) to model the revenue impact of incremental improvements at each stage.

Skills Demonstrated

SQL: CTEs, joins, CASE logic, aggregate functions
Power BI: DAX, calculated columns, ETL, data modeling, visualization
Python: Pandas, NumPy, Matplotlib, custom functions, statistical funnel modeling

Results & Recommendations

The dashboard provides product and sales teams with self-serve visibility into the order funnel, both company-wide and by client. This has already reduced ad-hoc analytics requests by approximately five hours per week.
Analysis revealed that nearly 50 % of orders drop off before users even enter the workflow, and fewer than 25 % of users successfully submit correct banking credentials. Python modeling shows that a 1 % increase in user interaction rate would generate roughly $285 in additional daily revenue, while a 1 % increase in completed bank-login attempts would add approximately $405 per day.
