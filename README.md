# RavenStack SaaS Customer Retention & Churn Analysis

## Project Overview

RavenStack is a fictional SaaS brand created for this Power BI portfolio case study.

The objective of this project was to analyze customer churn from a business perspective rather than simply build visualizations.

The dashboard explores three main questions:

1. What is the current state of customer and revenue health?
2. Which customer segments and factors are associated with churn?
3. Can product usage, satisfaction, or product reliability help explain retention behaviour?

The final report contains three interactive Power BI pages:

- Executive Overview
- Customer & Churn Analysis
- Product Usage & Retention

---

## Dashboard Preview

### 1. Executive Overview

![Executive Overview](assets/01_executive_overview.png)

This page provides a management-level view of:

- Total customers
- Active and churned customers
- Customer churn rate
- Monthly Recurring Revenue (MRR)
- Annual Recurring Revenue (ARR)
- Customer distribution by plan
- MRR contribution by plan
- Churn-event reasons
- Monthly MRR trend
- Geographic customer concentration

### Key Findings

- 110 of 500 customers have churned, resulting in a **22% customer churn rate**.
- Enterprise customers represent roughly **31% of the customer base** but contribute approximately **75% of total MRR**.
- Feature-related issues are the most frequently recorded churn-event reason, followed by budget and support.

---

## 2. Customer & Churn Analysis

![Customer & Churn Analysis](assets/02_customer_churn_analysis.png)

This page investigates where churn occurs and its financial impact.

Analysis includes:

- Churn-event trend
- Churned MRR
- Revenue churn rate
- Refund value
- Churn rate by industry
- Churn rate by country
- Churn rate by plan tier
- Refund amount by churn reason

### Key Findings

- Churned MRR is approximately **₹2.36M**.
- Revenue churn rate is approximately **20.8%**.
- DevTools records the highest displayed industry churn rate at approximately **31%**.
- Germany records the highest displayed country churn rate at approximately **32%**.
- Basic, Pro and Enterprise plan churn rates are all close to **22%**, suggesting that plan tier alone is not a major churn differentiator.
- Feature-related churn is associated with the highest refund amount.

---

## 3. Product Usage & Retention

![Product Usage & Retention](assets/03_product_usage_retention.png)

This page explores whether product engagement and reliability are related to retention.

Analysis includes:

- Average usage per customer by plan
- Average product usage for active vs churned customers
- Product error trends
- Feature-level normalized error rates
- Average satisfaction for active vs churned customers

### Key Findings

- Average usage is highly consistent across plan tiers, ranging from approximately **474–480 uses per customer**.
- Churned customers show slightly higher average usage than active customers.
- Customer satisfaction is also very similar across active and churned groups.
- This suggests that low product engagement alone does not explain churn in this dataset.
- Feature reliability requires targeted analysis, with the highest normalized feature error rate at approximately **65.58 errors per 1,000 uses**.

---

## Business Interpretation

A key takeaway from the analysis is that churn cannot be explained by a single factor.

Plan tier, product usage and satisfaction show relatively small differences between active and churned customers.

However, feature-related churn events, segment-level churn differences and revenue concentration indicate that customer retention efforts should focus on:

- Product and feature quality
- High-value customer segments
- Industry-specific retention strategies
- Customer feedback and churn-reason capture
- Revenue exposure among high-value accounts

---

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning
- KPI Development
- Customer Segmentation
- Churn Analysis
- Revenue Analysis
- Product Usage Analysis
- Data Visualization
- Business Storytelling

---

## Analytical Techniques Used

### Customer Churn Analysis

Customer churn was analyzed across:

- Industry
- Country
- Subscription plan
- Churn reason

### Revenue Analysis

MRR and revenue churn were used to understand the financial impact of customer loss.

### Product Engagement Analysis

Average usage per customer was used instead of relying only on total usage so customer segments of different sizes could be compared more fairly.

### Feature Reliability Analysis

Raw error counts can be misleading because highly used features naturally have more opportunities to generate errors.

To improve comparability, feature errors were normalized using:

**Errors per 1,000 Uses**

This helped identify features with comparatively high error rates rather than simply high error volumes.

---

## Dashboard Structure

The dashboard follows a simple analytical flow:

**Page 1 — What is happening?**

Overall customer and revenue health.

**Page 2 — Where and why is churn happening?**

Customer segmentation and financial impact.

**Page 3 — What product behaviour might help explain churn?**

Usage, satisfaction and product reliability.

---

## Key Skills Demonstrated

This project demonstrates my ability to:

- Convert raw data into business-focused KPIs
- Build relationships across multiple datasets
- Write DAX measures
- Design interactive dashboards
- Normalize metrics for fair comparisons
- Distinguish correlation from causation
- Translate analytical findings into business insights
- Build dashboards around business questions rather than visuals alone

---

## Important Note

RavenStack is a fictional brand created for this portfolio project.

The dashboard is intended to demonstrate Power BI, analytical thinking and business intelligence skills.

Monetary values are displayed in INR for the case-study presentation.

---

## Future Improvements

Future versions of the project could include:

- Customer-level churn risk scoring
- Cohort retention analysis
- Customer lifetime value
- Predictive churn modelling
- Drill-through customer profiles
- Automated Power BI Service refresh
- Customer segmentation based on behavioural patterns

---

## Author

**Aliva Roy**

MBA — Business Analytics  
B.Sc. Biotechnology  
Aspiring Data / Business Analyst

Skills: Power BI | SQL | Excel | Python | Business Analytics
