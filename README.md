
# Healthcare Revenue Optimization Analysis

## Objective
To analyze Accounts Receivable (AR) data and identify high-priority claims to improve revenue collection efficiency and reduce aging backlog.

---

## Dataset Overview
- Patient ID
- Claim ID
- Insurance/Payer
- Claim Amount
- Paid Amount
- Denial Status
- Aging Bucket (0–30, 30–60, 60–90, 90+)
- Work Status

---

## Business Problems Solved
- Identified high-value claims for prioritization
- Analyzed aging buckets to reduce >90 days AR
- Evaluated payer performance and delays
- Highlighted denial impact on revenue

---

## Approach
- Data Cleaning using SQL
- Data Transformation using CTEs and Window Functions
- Created priority scoring model:
  
  Priority Score = Claim Amount * Aging Weight * Denial Risk

---

## Tools Used
- SQL (MySQL)
- Power BI
- Excel

---

## Key Insights
- 30% of total revenue stuck in >90 days aging bucket
- Top 5 payers contributed to majority of delayed payments
- High-value claims (>₹50,000) formed only 15% volume but 60% revenue impact

---

## Dashboard Features
- AR Aging Analysis
- Payer-wise performance
- Denial trends
- Monthly collection trend

---

## Business Impact
- Improved prioritization strategy for claim processing
- Reduced risk of revenue loss from aging claims
- Enabled data-driven allocation of work to teams

---

## Repository Structure
- /data → Sample dataset
- /sql → SQL queries
- /dashboard → Power BI file (.pbix)
- /images → Dashboard screenshots

---

## 🔗 Author
Rahul Vishwakarma
