# Customer Churn — Behavioral Visualizations (Python)

## Goal
Explore churn behavior and identify patterns across:
- Contract type, tenure, billing, and service subscriptions
- Churn vs non-churn comparisons using interpretable plots

## Tech Stack
pandas • matplotlib • seaborn

## Visuals
- Churn by Contract: `[outputs/churn_by_contract.png](https://github.com/adapaania/data-visualisation/blob/main/01_Churn_Analysis/Outputs/churn_by_contract.png)`
- Tenure distribution by Churn: `outputs/tenure_by_churn.png`
- Monthly Charges vs Churn: `outputs/charges_vs_churn.png`

## Key Insights

- **Contract type is a strong indicator of churn behavior**  
  Customers on **month-to-month contracts** show a significantly higher churn rate compared to those on **one-year or two-year contracts**. Longer contract durations appear to provide stability and reduce short-term churn.

- **Churn is concentrated in the early stages of the customer lifecycle**  
  Customers with **low tenure** are more likely to churn, particularly within the first few months after onboarding. As tenure increases, churn rates decline and stabilize, indicating stronger customer retention over time.

- **Higher monthly charges are associated with increased churn**  
  Customers paying **higher monthly charges** tend to churn more frequently, suggesting price sensitivity or a mismatch between perceived value and cost.

- **Service usage patterns influence churn probability**  
  Certain service combinations and add-on subscriptions exhibit higher churn rates, indicating that service complexity or unmet expectations may contribute to customer dissatisfaction.


## How to run
```bash
pip install pandas numpy matplotlib seaborn jupyter
