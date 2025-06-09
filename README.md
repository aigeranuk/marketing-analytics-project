# marketing-analytics-project
Advanced marketing campaign end-to-end analysis

Analysis of the effectiveness of marketing campaigns across various online channels using advanced data science techniques, including cohort analysis, A/B testing, Bayesian inference, and causal inference.

# Marketing Analytics Project

**Advanced marketing campaign end-to-end analysis**

This project focuses on evaluating the effectiveness of marketing campaigns conducted across various online channels such as Email, Social Media, Search, and SMS. It combines multiple advanced data science techniques to uncover insights into user behavior, campaign performance, and ROI.

## Objectives

- Assess user retention and engagement over time using **cohort analysis**
- Evaluate campaign performance with **A/B testing**
- Apply **Bayesian statistical methods** for more robust inference
- Estimate **causal impact** of campaigns using **propensity score matching** and **treatment effect estimation**

## 🛠 Methods & Techniques

- Cohort Analysis
- Classical A/B Testing with `scipy.stats`
- Bayesian A/B Testing
- Causal Inference (Propensity Score Matching, Average Treatment Effect)
- Logistic Regression for Propensity Scores
- Nearest Neighbor Matching

## Data Features

Each row in the dataset represents a user interaction from a specific campaign, with fields such as:

- `User_ID`
- `Campaign_ID`
- `Date`, `Week`, `Month`, `Quarter`
- `Channel`, `Region`, `Segment`
- `Spend_USD`, `Impressions`, `Clicks`, `CTR`, `Conversion_Rate`, `CPA`, `CPC`
- Derived metrics: `Activity_Month`, `Cohort_Month`, `Cohort_Index`

## Notebooks and Scripts

- `cohort_analysis.ipynb`: Monthly retention analysis
- `ab_testing.py`: Classical and Bayesian A/B testing on CTR
- `causal_inference.py`: Propensity score modeling and ATT estimation
- `campaign_loop_analysis.py`: Campaign-by-campaign causal effect evaluation

## Sample Outputs

- Retention heatmaps by cohort
- Confidence intervals for conversion uplift
- ATT estimates per campaign
- Matched treatment-control distributions

##  How to Run

Clone the repo and run the notebooks or scripts in your Python environment (JupyterLab, JupyterHub, or VS Code).

```bash
git clone https://github.com/yourusername/marketing-analytics-project.git
cd marketing-analytics-project
