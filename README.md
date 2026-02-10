# customer_behaviour_analysis
End-to-end consumer analytics project using Python for data preparation, SQL for behavioural analysis, and Power BI for interactive dashboards and business insights.

Data Analytics Project

Overview

This project analyzes consumer shopping behavior to uncover insights related to customer loyalty, purchasing patterns, pricing impact, and demand drivers. The goal is to transform raw consumer data into actionable business insights using a structured analytics workflow—from data preparation to interactive dashboards and executive reporting.

The project demonstrates an end-to-end data analytics pipeline combining Python, SQL, Power BI, and presentation-ready reporting.

Dataset

The dataset contains customer demographics, purchase behavior, product details, pricing, and transaction history, including fields such as:

Customer demographics (age, gender, location)

Purchase details (category, size, season, payment method)

Behavioral metrics (previous purchases, purchase frequency)

Pricing signals (discount applied, purchase amount)

Experience indicators (review ratings, shipping type)

The dataset was anonymized and used strictly for analytical and portfolio purposes.

Tools & Technologies

Python: Data loading, cleaning, feature engineering, exploratory analysis

SQL (MySQL / SQL Server): Customer segmentation and behavioral analysis

Power BI: Interactive dashboards, KPIs, and data visualization

Gamma: Executive presentation (PPT-style report)

Project Workflow
1. Data Loading (Python)

Loaded the dataset using pandas

Inspected structure, data types, and basic statistics

Validated row counts and column consistency

2. Exploratory Data Analysis (EDA)

Analyzed distributions of age, purchase amounts, and ratings

Reviewed category-level sales and customer behavior

Identified missing values, outliers, and inconsistencies

3. Data Cleaning & Feature Engineering

Handled missing and invalid values

Standardized column formats and data types

Created derived features such as:

Age groups

Purchase frequency metrics

Loyalty indicators based on prior purchases

4. SQL Analysis (MySQL / SQL Server)

Loaded cleaned data into a relational database

Wrote SQL queries to:

Segment customers by behavior and loyalty

Analyze repeat purchases and demand patterns

Evaluate pricing and discount effectiveness

Aggregated results for dashboard consumption

5. Dashboard Development (Power BI)

Built a multi-page interactive dashboard including:

Executive Overview: Key KPIs, revenue drivers, top categories

Customer Loyalty & Purchase Behaviour: Repeat purchases, subscriptions, frequency

Pricing & Promotions Analysis: Discount usage, order value comparison

Features include slicers, KPIs, drill-down visuals, and clean layout design.

6. Reporting & Presentation

Created an Executive Insights Summary highlighting key findings and recommendations

Developed a presentation deck using Gamma to communicate insights to non-technical stakeholders

Dashboard Highlights

Clear visibility into customer loyalty drivers

Identification of high-value customer segments

Insights into how discounts influence purchasing behavior

Category-level demand patterns to support planning decisions

Key Results

Revealed strong links between repeat purchasing and subscription status

Identified top-performing product categories driving the majority of revenue

Highlighted opportunities to refine discount strategies to protect order value

Enabled faster, data-driven decision-making through interactive reporting

How to Run the Project
Python Analysis

Clone this repository

Install dependencies:

pip install pandas numpy matplotlib seaborn


Run the Python notebook/script for EDA and data cleaning

SQL Analysis

Import the cleaned dataset into MySQL or SQL Server

Run the provided SQL queries to generate analytical tables

Power BI Dashboard

Open the .pbix file in Power BI Desktop

Refresh data connections if needed

Use slicers and filters to explore insights

Notes

This project is designed for portfolio and learning purposes

No proprietary or confidential data is included

The workflow mirrors real-world analytics and BI projects

Author

Besty Ama Nyarko
Data Analyst | Business Intelligence Analyst
