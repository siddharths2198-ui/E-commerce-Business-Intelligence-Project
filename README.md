# E-commerce-Business-Intelligence-Project
This project provides a comprehensive 360-degree analysis of Olist, the largest department store in Brazilian marketplaces. Using a dataset of 100k orders from 2016 to 2018, I developed a three-tier dashboard suite to identify operational bottlenecks and growth opportunities.
# The Problem
Olist faced challenges in three main areas:

Retention: High customer churn and low repeat purchase rates.

Logistics: Geographic delivery delays affecting customer satisfaction.

Revenue: A lack of clarity on which payment strategies drive high-ticket sales.

# Technical Workflow
1. Data Cleaning & Transformation (SQL)
Before visualization, I used MySQL to clean and restructure the raw data:

ETL Process: Joined 8+ relational tables (Orders, Items, Payments, Products, etc.).

Handling Nulls: Managed missing delivery timestamps to ensure accurate logistics KPIs.

Calculated Fields: Created custom logic for Loyalty Status (New vs. Repeat) and Delivery Accuracy (Days before/after deadline).

2. Strategic Visualization (Tableau)
I built three distinct dashboards to serve different stakeholders:

Revenue Dashboard: Executive view of $15.2M in sales and geographic distribution.

Logistics Audit: Stress-test analysis identifying a 21.4% failure rate in specific regions (AL/MA).

Customer Strategy: Correlation analysis between installment plans and Average Order Value (AOV).

# Key Insights
Credit Dependency: 75% of revenue is driven by Credit Cards; AOV increases by ~200% when 10+ installments are used.

Retention Gap: Only 6.08% of customers are repeat buyers, highlighting a critical need for loyalty programs in the "Health & Beauty" category.

The Buffer Insight: Most "On-time" orders arrive 10-15 days before the promised deadline, suggesting Olist's delivery estimates are overly conservative.

### Visual Insights & Analytics
I created an interactive 3-tier dashboard suite to analyze Brazil's market dynamics.

#### 1. Revenue & Sales Performance
![Revenue Dashboard](Revenue_Dashboard (1).png)

#### 2. Logistics & Supply Chain
![Logistics Dashboard]()

#### 3. Customer Segmentation
![Customer Dashboard]()

