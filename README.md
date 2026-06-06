# Customer Behaviour Analysis

## Project Overview

This project analyzes customer shopping behavior to uncover patterns in purchasing habits, customer demographics, product preferences, and promotional effectiveness. The analysis combines **Python**, **SQL**, and **Power BI** to create a complete data analytics workflow from data cleaning to business insights and dashboard visualization.

## Objectives

* Understand customer purchasing behavior.
* Identify trends across age groups and product categories.
* Analyze the impact of discounts and promotional campaigns.
* Create a structured database for efficient querying.
* Develop interactive dashboards for business decision-making.

---

## Dataset

The dataset contains customer shopping information, including:

* Customer demographics (Age, Gender)
* Product categories
* Purchase amount
* Review ratings
* Discounts applied
* Purchase frequency
* Seasonal shopping trends
* Payment methods
* Shipping preferences

---

## Tools & Technologies

### Python

* Pandas
* NumPy
* SQLAlchemy
* PostgreSQL Connector (psycopg2)

### SQL

* PostgreSQL
* Data storage and querying
* Business intelligence queries

### Power BI

* Interactive dashboards
* KPI tracking
* Customer segmentation analysis
* Sales and category performance visualization

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

1. Loaded and explored the dataset using Pandas.
2. Checked data types and summary statistics.
3. Identified and handled missing values.
4. Filled missing review ratings using category-wise median values.
5. Standardized column names:

   * Converted to lowercase
   * Replaced spaces with underscores
6. Created derived features:

   * **Age Group** segmentation:

     * Young Adult
     * Adult
     * Middle-aged
     * Senior
   * **Purchase Frequency Days** by converting frequency categories into numeric values.
7. Removed redundant columns to improve dataset quality.

---

## Database Integration

The cleaned dataset was connected and exported to a PostgreSQL database using SQLAlchemy.

### Database Details

* Database: PostgreSQL
* Table: Customer Analysis

This enables advanced SQL querying and integration with reporting tools such as Power BI.

---

## SQL Analysis

SQL was used to answer business questions such as:

* Which product categories generate the highest revenue?
* What is the average purchase amount by age group?
* Which customer segments purchase most frequently?
* How do discounts affect spending behavior?
* What are the top-performing categories and seasons?

---

## Power BI Dashboard

The Power BI dashboard provides:

### Key Metrics

* Total Revenue
* Average Purchase Value
* Customer Count
* Average Review Rating

### Visualizations

* Revenue by Product Category
* Revenue by Age Group
* Seasonal Purchase Trends
* Discount Impact Analysis
* Purchase Frequency Distribution
* Customer Demographic Breakdown

### Business Insights

* High-value customer segments
* Best-performing product categories
* Seasonal demand patterns
* Promotional campaign effectiveness

---

## Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning (Python)
     ↓
Feature Engineering
     ↓
PostgreSQL Database
     ↓
SQL Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
```

---

## Key Learnings

* Data Cleaning and Preprocessing using Pandas
* Feature Engineering techniques
* Database integration with PostgreSQL
* SQL querying for business analysis
* Dashboard development in Power BI
* End-to-end analytics project development

---

## Future Improvements

* Customer Lifetime Value (CLV) Analysis
* Customer Segmentation using Machine Learning
* Sales Forecasting Models
* Automated ETL Pipeline
* Real-time Dashboard Integration

---

## Author

**Uttkarsh Mahajan**

Data Analyst | SQL | Python | Power BI

This project demonstrates an end-to-end data analytics workflow, transforming raw customer shopping data into actionable business insights through Python, SQL, PostgreSQL, and Power BI.

