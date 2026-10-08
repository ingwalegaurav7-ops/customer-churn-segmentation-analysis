# Customer Churn Segmentation & Rule-Based Risk Analysis

## Project
Data Analytics – Task 3: Segmentation and Recommendation Model

## Objective
Segment customers by behavior and create a transparent, reproducible churn-risk score.

## Decision question
Which customer groups should a fictional subscription team contact first to reduce avoidable churn?

## Files
- `customer_churn_segmentation_analysis.ipynb` — complete analysis notebook
- `customer_churn_sample (1).csv` — supplied dataset
- `customer_segments.csv` — scored customer/segment table

## Risk scoring
- Monthly contract: +2
- 4+ support tickets: +2
- 2–3 support tickets: +1
- Tenure <= 12 months: +2
- Tenure 13–24 months: +1
- Monthly charges >= ₹100: +1

Risk bands:
- 0–1: Low
- 2–3: Medium
- 4+: High

`Churn` is not used to calculate the score. It is used only after scoring to evaluate the rule on the supplied sample.

## Results
- High Risk: 5 customers; 5 churned; 100% observed churn rate
- Medium Risk: 4 customers; 2 churned; 50% observed churn rate
- Low Risk: 6 customers; 0 churned; 0% observed churn rate

## Recommendation
Prioritize proactive retention outreach to High-Risk customers, then selectively address Medium-Risk customers. Maintain normal engagement for Low-Risk customers.

## Limitation
This is a fictional sample of only 15 customers. The observed churn rates are not population estimates and do not establish causation.
