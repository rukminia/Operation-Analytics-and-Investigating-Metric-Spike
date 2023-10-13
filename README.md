# Operation-Analytics-and-Investigating-Metric-Spike
Operational Analytics is a crucial process that involves analyzing a company's end-to-end operations. This analysis helps identify areas for improvement within the company. 
Case Study 1: Job Data Analysis
I worked with a table named job_data with the following columns:

job_id: Unique identifier of jobs
actor_id: Unique identifier of actor
event: The type of event (decision/skip/transfer).
language: The Language of the content
time_spent: Time spent to review the job in seconds.
org: The Organization of the actor
ds: The date in the format yyyy/mm/dd (stored as text).

Tasks:

Jobs Reviewed Over Time:

Objective: Calculate the number of jobs reviewed per hour for each day in November 2020.
Your Task: Write an SQL query to calculate the number of jobs reviewed per hour for each day in November 2020.

Throughput Analysis:
Objective: Calculate the 7-day rolling average of throughput (number of events per second).
Your Task: Write an SQL query to calculate the 7-day rolling average of throughput. Additionally, explain whether you prefer using the daily metric or the 7-day rolling average for throughput, and why.

Language Share Analysis:
Objective: Calculate the percentage share of each language in the last 30 days.
Your Task: Write an SQL query to calculate the percentage share of each language over the last 30 days.

Duplicate Rows Detection:
Objective: Identify duplicate rows in the data.
Your Task: Write an SQL query to display duplicate rows from the job_data table.


Case Study 2: Investigating Metric Spike
I worked with three tables:
users: Contains one row per user, with descriptive information about that user’s account.
events: Contains one row per event, where an event is an action that a user has taken (e.g., login, messaging, search).
email_events: Contains events specific to the sending of emails.
Tasks:

Weekly User Engagement:
Objective: Measure the activeness of users on a weekly basis.
Your Task: Write an SQL query to calculate the weekly user engagement.

User Growth Analysis:
Objective: Analyze the growth of users over time for a product.
Your Task: Write an SQL query to calculate the user growth for the product.

Weekly Retention Analysis:
Objective: Analyze the retention of users on a weekly basis after signing up for a product.
Your Task: Write an SQL query to calculate the weekly retention of users based on their sign-up cohort.
Weekly Engagement Per Device:

Objective: Measure the activeness of users on a weekly basis per device.
Your Task: Write an SQL query to calculate the weekly engagement per device.

Email Engagement Analysis:
Objective: Analyze how users are engaging with the email service.
Your Task: Write an SQL query to calculate the email engagement metrics.
