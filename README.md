# SQL for Data Analysis - Investigating Metric Spike


 
The objective was to use SQL to extract insights, analyze user behavior, and work with structured data using a dataset - user activity and email engagement data.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📁 Dataset Description
Three tables were created and populated with CSV data:

users: User profile details – user_id, account creation time, activation date, company_id, language, and state.

events: User activity logs – timestamped events with types and device information.

email_events: Email interactions like opens, clicks, and campaign sends.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


✅ Tasks Completed
1. Basic SQL Operations
Created tables and imported CSV data.

Converted date strings into proper DATETIME formats.

2. Data Analysis Queries
Weekly active users per user.

User growth trends by signup week.

Retention analysis based on signup cohorts.

Weekly activeness per device.

Email engagement tracking (opens, clicks, campaigns).

3. Advanced SQL Concepts
✅ Subquery: Identify users with event counts above the average.

✅ View: Created weekly_device_activity for simplified active user tracking.

✅ Index: Added index on user_id, occurred_at to optimize event queries.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🛠 Tools Used
MySQL Workbench

CSV files

SQL (DDL, DML, DQL)





