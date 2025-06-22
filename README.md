📊 Hero FinCorp - Loan Performance & Risk Analysis

Author: Adarsh Singh Role: Data Analyst

🎯 Project Objective

To provide Hero FinCorp with actionable insights to:

❌ Minimize loan defaults by identifying high-risk customers and regions.

✅ Optimize branch operations by improving processing time and recovery rates.

💸 Enhance profitability through strategic customer segmentation and interest income analysis.

📂 Dataset Overview

Total Tables Used: 6

customers.csv

loans.csv

defaults.csv

transactions.csv

applications.csv

branches.csv

📊 Key Analysis Performed

1. Default Risk Analysis

High default rates identified in low-income, low-credit score segments.

Defaults peak 60–90 days post-disbursal, especially during Oct–Dec.

2. Branch Performance

Fastest branches: Mumbai Central, Bangalore North.

Most rejections: East Delhi branch.

Legal actions improve recovery rate by ~12%.

3. Profitability Drivers

Most profitable: Business & Vehicle loans.

High EMI (> ₹20,000) increases default risk by 35%.

4. Customer Segmentation

Tagged customers by income, credit score, and loan status.

Identified "High Risk" vs. "High Value" segments.

5. Time-Series Trends

Loan disbursals show steady growth over 5 years.

Seasonal dips in April–May and spikes around festive periods.

6. Recovery Effectiveness

Overall recovery rate: ~24%.

Legal action improves outcomes but is underutilized.

📝 Strategic Recommendations

Area

Action

Defaults

Deploy predictive risk model using credit score, EMI, and income

Branch Ops

Track disbursement delays; automate low-risk approvals

Profitability

Focus on Business & Vehicle loans; cap EMI-to-income ratio

📈 Visual Insights

Find all plots, charts, and heatmaps in the visuals/ folder.

Default rate by region

EMI vs. Default boxplot

Interest income by loan purpose

Time-series disbursement trends


HeroFinCorp-Loan-Analysis/
├── notebooks/
│   └── HeroFinCorp_EDA.ipynb
├── visuals/
│   ├── default_rate_by_region.png
│   ├── emi_vs_default_boxplot.png
│   └── ...
├── HeroFinCorp_Key_Insights_Report.pdf
├── recommendations_summary.pdf
├── README.md
