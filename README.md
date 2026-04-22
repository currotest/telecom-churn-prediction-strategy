# telecom-churn-prediction-strategy
Machine Learning model to identify high-risk customers and quantify a €428k retention strategy ROI

# 🛡️ Churn Shield: Strategic Customer Retention System (566% ROI)

This project develops a commercial intelligence system for a Telecommunications provider. It identifies high-risk customers and quantifies the financial impact of a targeted rescue strategy.

## 📈 Business Impact
- **At-Risk Population Identified:** 1,914 customers (optimized at 0.4 threshold).
- **Protected Annual Revenue:** €566,215.
- **Estimated Net Profit:** **€428,262.45** (after campaign costs).
- **Efficiency:** 566% ROI.

---

## 📊 Visualizing the Strategy

### 1. Revenue Leakage & Prioritization
We identify where the revenue "leaks" (Sankey) and prioritize customers based on their financial value and churn probability.

![Sankey Diagram](images/Sankey_diagram.png)
![Priority Matrix](images/Decission_matrix.png)

### 2. Risk Distribution
The model doesn't just give a binary answer; it assigns a probability. This allows us to see the concentration of high-risk customers across the portfolio.

![Churn Probabilities](images/churn_probabilities.png)

---

## ⚙️ Model Performance & Strategic Tuning

### 3. Threshold Sensitivity Analysis
Why 0.4? We conducted a sensitivity analysis to find the "Sweet Spot" where we capture enough churners to justify the campaign cost without overwhelming the budget with false positives.

![Sensitivity Analysis](images/sensitive_analysis.png)
![Confusion Matrix](images/confusion_matrix.png)

---

## 🧠 Explainable AI (XAI): The "Why" Behind Churn
Using **SHAP (SHapley Additive exPlanations)**, we move beyond the "Black Box" to understand exactly which factors drive a customer to leave.

### 4. Global Feature Impact
The SHAP Summary plot highlights that **Contract Type**, **Number_of_referrals** and **Monthly Charges** are the most critical drivers.

![SHAP Summary](images/shap_summary_plot.png)

### 5. Deep Dive: Monthly Charges
The dependence plot reveals a clear "Risk Zone": as monthly charges exceed €70, the probability of churn spikes significantly, especially for certain contract types.

![SHAP Dependence](images/shap_dependence_plot_monthly_charge.png)

---

## 🛠️ Tech Stack
- **Python / Pandas:** Financial data auditing.
- **Scikit-Learn:** Random Forest & Threshold Optimization.
- **Plotly:** Strategic Visualizations.
- **SHAP:** Model Interpretability.

## 📂 Project Structure
- `data/`: Datasets used in the analysis.
- `notebooks/`: End-to-end Jupyter Notebook.
- `images/`: High-resolution exports of all charts.

---
*Developed for strategic business decision-making.*
