# Salifort Motors Employee Retention Project

## Overview
The objective of this project is to build a predictive machine learning model to identify employees at risk of leaving Salifort Motors[cite: 2, 3]. By identifying the key drivers of employee turnover, the HR department can proactively intervene to retain highly skilled talent in a competitive market[cite: 2, 3].

## Methodology
The project follows the PACE (Plan, Analyze, Construct, Execute) framework[cite: 1, 2]. 
* **Data Processing:** Cleaned a dataset of 14,999 records, keeping real-world outliers (such as highly tenured employees) intact for better model learning[cite: 2, 3].
* **Modeling:** Built and evaluated ensemble models including Random Forest and XGBoost[cite: 1, 2, 3]. 

## Key Results & Insights
* **Champion Model:** XGBoost was selected as the final model due to its high processing speed and strong resistance to overfitting, achieving an overall Accuracy and F1-score of ~99%[cite: 2, 3].
* **The "Extreme Edges" Phenomenon:** Turnover is heavily concentrated at the extreme ends of the operational spectrum. Employees with excessive workloads or very few projects leave at high rates, while the "middle core" remains stable[cite: 2, 3].
* **Top Drivers of Churn:** Operational bandwidth is the primary driver[cite: 3]. The top predictive features were:
  1. `average_monthly_hours` (Importance Score: 905.0)[cite: 3].
  2. `satisfaction_level` (Importance Score: 791.0)[cite: 3].
  3. `last_evaluation` (Importance Score: 726.0)[cite: 3].

## Business Recommendations
1. **Workload Rebalancing:** Strictly monitor average monthly hours to prevent burnout among high-performing employees[cite: 3].
2. **"Employee Portfolios" System:** Shift from point-in-time data to a continuous tracking system that evaluates skill acquisition every 6 months to foster loyalty[cite: 2, 3].
3. **Pilot Phase Deployment:** Launch a shadow deployment of the XGBoost model to validate predictions in real-time without disrupting current HR workflows[cite: 3].

## Files Included
* `HR_capstone_dataset.ipynb`: The complete Python code and analysis[cite: 1].
* `Project_Proposal.pdf`: Detailed initial proposal and strategy[cite: 2].
* `Executive_Summary.pdf`: High-level summary of findings and recommendations[cite: 3].
