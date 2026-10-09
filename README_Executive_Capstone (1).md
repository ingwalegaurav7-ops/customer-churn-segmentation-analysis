# Executive Analytics Capstone: Customer Churn

## Decision question
Which customer groups should a fictional subscription team contact first to reduce avoidable churn?

## Executive recommendation
Run a small retention pilot focused on customers with 4+ support tickets and newer month-to-month customers. Resolve recurring issues and offer proactive onboarding/check-ins. Do not scale until a comparison group shows a repeatable improvement.

## Five findings
1. **Overall churn:** 7 of 15 customers churned (46.7%) in this tiny sample.
2. **Contract type:** 7/7 month-to-month customers churned; 0/8 one-year/two-year customers churned.
3. **Support tickets:** 5/5 customers with 4+ tickets churned; 0/6 with 0–1 tickets churned.
4. **Tenure:** 6/6 customers with 12 months or less tenure churned; 0/4 with 25+ months churned.
5. **Subscription:** 5/7 Basic customers churned; 0/4 Enterprise customers churned.

## Data quality
- 15 rows and 11 columns.
- No missing values or exact duplicate rows detected.
- `CustomerID` is an identifier, not a measure.
- The supplied CSV uses different column names from the general field guide; this analysis uses the actual CSV columns.

## Recommendation and measurement
- Review support cases for customers with 4+ tickets.
- Contact newer month-to-month customers with proactive support.
- Run a 3–6 week pilot with a comparison group where practical.
- Track follow-up churn, issue resolution, repeat tickets, contact rate, and cost per retained customer.

## Limitations
This is a 15-row synthetic sample. Descriptive patterns do not prove causation and are not reliable population estimates. The data does not provide an observation timestamp/window, intervention effectiveness, campaign costs, margin, or customer lifetime value. Any impact scenarios in the PDF/slides are illustrations, not forecasts.

## Files
- `Executive_Analytics_Capstone.pdf` — executive brief
- `Executive_Analytics_Capstone_Presentation.pptx` — presentation slides
- `customer_churn_sample.csv` — supplied source data (add this file to the repository if permitted)
