# 📊 Telecommunications Customer Churn Analysis (Tableau Dashboard)

## 🔗 View the Dashboard

<a href="https://public.tableau.com/app/profile/shane.mcbryde/viz/D210-RepresentationandReporting_17107923311500/PerformanceAssessment" target="_blank">![tableau-public-link](https://img.shields.io/badge/Tableau%20Public-View%20Dashboard-red.svg?logo=tableau)</a>

---

## 🎯 Project Overview & Objectives
This project provides an in-depth analysis of telecommunications customer churn. The primary goal is to identify the specific factors driving customer churn and propose data-backed strategies to increase customer retention. A central theme explored throughout the dashboard is whether aggressive promotion of streaming and add-on services, especially to new or monthly-contract customers, may be inadvertently increasing churn. The analysis reveals the key insight that higher short-term revenue may be coming at the cost of long-term customer relationships, as churned customers consistently have higher monthly charges and shorter contract durations.

---

## 📁 Data Sources

- **Telecommunications Customer Churn Dataset**  
  In-house customer data, including demographics, subscription services, usage, and churn status.

- **FCC Consumer Complaints Dataset**  
  Publicly available data compiled by the FCC, detailing telecommunications consumer complaints by category and geography.

---

## 🧭 Dashboard Breakdown

The Tableau dashboards are designed to provide a comprehensive, interactive view of the data:

- **Churn Rates Dashboard**  
  A summary of core metrics (counts, percentages, and usage) for churned vs. retained customers. It highlights the significant payment disparity between the two groups.

- **Contract Duration Dashboard**  
  This dashboard compares churned and retained customers across different contract types. It reveals that longer-term contracts are strongly associated with higher retention rates and lower churn, emphasizing the stabilizing effect of extended commitments.

- **Add-Ons and Streaming Services Dashboards**  
  These dashboards provide a detailed look at customer adoption of add-ons and streaming services, differentiated by contract type. The primary metric is the percent difference in churned vs. retained customer distribution for each service.

- **Customer Demographics Dashboard**  
  This dashboard explores the churned/retained differences across various demographic categories, allowing for the identification of specific customer segments with high churn risk.

- **FCC Complaints Rate Dashboard**  
  This dashboard provides a summary of FCC complaint data. The included Complaint vs. Churn Percent graph allows for state-level comparison of the most common complaint type and its relationship to customer churn rates.

---

## 📈 Key Findings & Insights

The analysis reveals a strong correlation between customer churn and financial factors, suggesting that a portion of the customer base may be over-extended, leading them to discontinue their service. Key insights include:

- **Churned customers pay more**  
  On average, churned customers pay 22% more than retained customers and dedicate a 30% higher portion of their income to their service. This trend is consistent across all contract durations and service types.

- **Contract duration matters**  
  Customers on longer-term contracts are significantly more likely to be retained. Retention rates for one-year and two-year contracts are 484% and 590% higher than churn rates, respectively, highlighting the value of long-term commitments.

- **Billing complaints correlate with churn**  
  Analysis of the FCC complaints data reveals that billing is the most frequent complaint nationwide. Furthermore, all states with above-median churn rates also report billing as their most frequent complaint, suggesting a direct link between billing disputes and customer churn.
  
## 💡 Strategic Recommendations

Based on the analysis, the following strategies are proposed to reduce churn and foster long-term customer relationships:

1. **Re-evaluate sales strategies for add-ons and streaming services.** Avoid aggressively marketing these services to new customers, particularly those on a monthly contract, as this combination is highly correlated with increased churn.
2. **Incentivize transitions to longer-term contracts.** Offer promotions, such as free trials for streaming services or add-ons, to encourage monthly customers to transition to more stable one-year or two-year contracts.
3. **Investigate and address billing issues.** Prioritize resolving billing-related complaints to mitigate their strong negative correlation with customer churn.

---

## 🧠 Closing Thoughts

This dashboard was designed to support strategic decision-making around customer retention. It combines financial, behavioral, and complaint data to surface actionable insights.
