# Customer Segmentation using RFM Analysis
**Tools:** Python · Pandas · Matplotlib · Seaborn
**Dataset:** Online Retail II (UCI/Kaggle) — 1M+ transactions | 5,878 customers

## Problem
Identify distinct customer groups from 2 years of retail transaction
data to help the business prioritize marketing and retention spend.

## Approach
- Cleaned 1,067,371 raw transactions down to 805,549 usable records
- Calculated Recency, Frequency, and Monetary scores for each customer
- Segmented 5,878 customers into 6 behavioral groups using RFM methodology

## Key Findings
- Champions (25% of customers) drive 69.3% of total revenue — £12.3M
- At Risk segment holds £1.6M in revenue — urgent retention opportunity
- 25.9% of customers are Lost — re-acquisition cost likely exceeds value
- 80/20 rule confirmed: top customer tier disproportionately drives revenue

## Recommendations
- Protect Champions with VIP loyalty programs and early access offers
- Launch targeted win-back campaign for 824 At Risk customers
- Upsell Potential Loyalists to increase average order value
- Investigate root cause of churn in Lost Customers segment

## Files
- `notebook/rfm_analysis.ipynb` — full analysis notebook
- `segment_distribution.png` — customer count by segment
- `revenue_by_segment.png` — revenue contribution by segment
- `revenue_share_pie.png` — revenue share breakdown
