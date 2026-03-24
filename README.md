# Project Background
Flipkart, founded in 2007, is a leading Indian e-commerce marketplace connecting buyers and sellers across multiple product categories, where customer support performance directly impacts CSAT, resolution efficiency, and retention.
<br><br>
Due to a decline in retention rates, this project analyzes customer support call data to identify key issues affecting customer experience.
It evaluates factors like issue type, resolution time, channels, and regional trends to uncover actionable insights for improving service quality and retention.<br><br>
Insights and recommendations are provided on the following key areas:
- Issue Type & CSAT Analysis: Evaluation of customer issues and their impact on CSAT

- Channel & Call Center Performance: Analysis of support channels and call centers to assess variations in CSAT and identify performance gaps across high-volume centers.

- Regional & Temporal Trends: Examination of CSAT variations across states, along with trends over time and day-level patterns affecting customer satisfaction.

- Operational Metrics & Sentiment Impact: Assessment of response time, call duration, and customer sentiment to determine their influence on CSAT

# Data Structure

The dataset consists of **30,000 customer support interaction records**, where each row represents a unique customer service call. It captures customer details, interaction attributes, and performance metrics used to analyze customer satisfaction (CSAT) and retention.

| Column Name               | Data Type       | Description                                                                 |
|--------------------------|-----------------|-----------------------------------------------------------------------------|
| id 🔑                     | INT             | Unique identifier for each customer interaction                             |
| customer_name            | VARCHAR         | Name of the customer                                                        |
| Gender                   | VARCHAR         | Gender of the customer (e.g., Male, Female)                                 |
| sentiment                | VARCHAR         | Customer sentiment (Positive, Neutral, Negative)                            |
| csat_score               | INT             | Customer satisfaction score (e.g., 1–5 scale)                               |
| call_timestamp           | DATETIME        | Date and time of the customer interaction                                   |
| reason                   | VARCHAR         | Reason for the call (e.g., Billing, Service Outage)                         |
| city                     | VARCHAR         | City of the customer                                                        |
| state                    | VARCHAR         | State of the customer                                                       |
| channel                  | VARCHAR         | Support channel (Call Center, Chatbot, etc.)                                |
| response_time            | FLOAT / INT     | Time taken to respond (in seconds/minutes)                                  |
| call_duration_minutes    | FLOAT           | Duration of the call in minutes                                             |
| call_center              | VARCHAR         | Call center handling the interaction (e.g., Delhi, Mumbai)                  |

