# Salifort Motors Employee Retention Project

## Overview
The objective of this project is to build a predictive machine learning model to identify employees at risk of leaving Salifort Motors. By identifying the key drivers of employee turnover, the HR department can proactively intervene to retain highly skilled talent in a competitive market.

## Methodology
The project follows the PACE (Plan, Analyze, Construct, Execute) framework. 
* **Data Processing:** Cleaned a dataset of 14,999 records, keeping real-world outliers (such as highly tenured employees) intact for better model learning.
* **Modeling:** Built and evaluated ensemble models including Random Forest and XGBoost. 

## Key Results & Insights
* **Champion Model:** XGBoost was selected as the final model due to its high processing speed and strong resistance to overfitting, achieving an overall Accuracy and F1-score of ~99%.
* **The "Extreme Edges" Phenomenon:** Turnover is heavily concentrated at the extreme ends of the operational spectrum. Employees with excessive workloads or very few projects leave at high rates, while the "middle core" remains stable.
* **Top Drivers of Churn:** Operational bandwidth is the primary driver. The top predictive features were:
  1. `average_monthly_hours` (Importance Score: 905.0)
  2. `satisfaction_level` (Importance Score: 791.0)
  3. `last_evaluation` (Importance Score: 726.0)

## Business Recommendations
1. **Workload Rebalancing:** Strictly monitor average monthly hours to prevent burnout among high-performing employees.
2. **"Employee Portfolios" System:** Shift from point-in-time data to a continuous tracking system that evaluates skill acquisition every 6 months to foster loyalty.
3. **Pilot Phase Deployment:** Launch a shadow deployment of the XGBoost model to validate predictions in real-time without disrupting current HR workflows.

## Files Included
* `Activity_ Course 7 Salifort Motors project lab.ipynb`: The complete Python code and analysis.
* `Project_Proposal.pdf`: Detailed initial proposal and strategy.
* `Executive_Summary.pdf`: High-level summary of findings and recommendations.
