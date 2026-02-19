Data Analyst Intern Assignment

Overview

This project analyzes user engagement, purchase conversion funnel, and customer purchasing behavior over a two-week period using three datasets:

• Events Data
• Orders Data
• Customers Data

The objective of this assignment is to clean the datasets, build analytical metrics, and derive meaningful business insights through structured visualization.

Data Preparation

The following data preparation steps were performed:

• Converted event_date and order_date into proper date format
• Removed duplicate records from Orders and Customers datasets
• Filtered only valid orders (order_status = "Valid")
• Standardized user_id and customer_id for accurate relationship mapping
• Corrected column naming inconsistencies

Only cleaned and validated data was used for analysis.

Funnel Analysis

The purchase funnel was analyzed using the following metrics:

• Total unique users who triggered events
• Total unique users who placed valid orders
• Conversion Rate

Conversion Rate Formula:

Conversion Rate = Users with Valid Orders ÷ Users with Events

A time-series visualization was created to compare:

• Daily Active Users
• Daily Ordering Customers

This analysis evaluates how user engagement translates into purchase behavior over time.

Customer Behavior Analysis

Orders data was joined with customer data to analyze purchasing patterns based on:

• Acquisition Channel
• City

Revenue was aggregated to identify which acquisition channel generates the highest sales contribution.

Key Insight

The acquisition channel generating the highest revenue demonstrates stronger customer value and purchasing behavior compared to other channels.

This indicates that marketing efforts in this channel are more effective in driving revenue performance.

Tools Used

• Power BI (Data Cleaning, Data Modeling, Visualization)

Assumptions

• user_id corresponds to customer_id
• Only valid orders were considered for revenue analysis
• Duplicate records were removed before metric calculation

Conclusion

This analysis demonstrates the relationship between user engagement and purchasing behavior.

By structuring a clear funnel and revenue breakdown, actionable insights can be derived to improve customer acquisition strategies and conversion performance.
