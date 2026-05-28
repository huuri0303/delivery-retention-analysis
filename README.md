# delivery-retention-analysis
By using Olist Brazilian E-Commerce Dataset, I verify the impact of delivery delays on customer satisfaction

# Impact of Delivery Delays on Customer Retention in E-commerce Platforms

## Project Overview

Customer experience is one of the most important factors in e-commerce platforms.
Among various factors, delivery quality can significantly affect customer satisfaction and long-term retention.

This project investigates the following hypothesis:

> Delivery delays negatively impact customer review scores and reduce repeat purchase rates.

Using a public e-commerce dataset, I conducted SQL-based data analysis, Python-based visualization and statistical analysis, and AI-powered review analysis to identify actionable business insights and propose operational improvements.

---

## Business Problem

Delivery delays may lead to:

* Lower customer satisfaction
* Negative reviews
* Reduced customer retention
* Decreased long-term customer value (LTV)

Understanding the relationship between delivery performance and customer behavior is important for improving both user experience and business performance.

---

## Hypotheses

* Longer delivery delays lead to lower review scores
* Customers with lower review scores are less likely to make repeat purchases
* Improving delivery quality can improve customer retention

---

## Dataset

Dataset used:

* Olist Brazilian E-Commerce Dataset

Source:

* https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Main tables used:

* orders
* order_reviews
* customers
* order_items
* products

---

## Technologies Used

### SQL

* PostgreSQL
* JOIN
* GROUP BY
* CTE
* Window Functions

### Python

* pandas
* matplotlib
* scikit-learn

### AI / NLP

* OpenAI API
* Review summarization
* Complaint extraction

---

## Analysis Performed

### SQL Analysis

* Delivery delay calculation
* Review score aggregation
* Repeat purchase analysis
* Cohort analysis

### Python Analysis

* Delay distribution visualization
* Correlation analysis
* Regression analysis
* Retention analysis

### AI Analysis

* Summarization of negative reviews
* Extraction of delivery-related complaints
* Customer feedback pattern analysis

---

## Key Findings

* Orders with longer delivery delays tended to receive lower review scores
* Customers who gave low review scores showed lower repeat purchase rates
* Delivery-related complaints frequently appeared in negative reviews

---

## Business Recommendations

Based on the analysis, the following improvements are proposed:

* Proactive notification system for delayed orders
* Seller ranking system incorporating delivery quality
* AI-powered review monitoring system
* Retention campaigns for customers affected by delivery delays

---

## Repository Structure

```text
delivery-retention-analysis/
│
├── sql/
├── notebooks/
├── images/
├── ai/
├── docs/
└── README.md
```

---

## Future Improvements

* Build a delivery delay prediction model
* Apply causal inference methods
* Develop real-time monitoring dashboards
* Conduct customer segmentation analysis

