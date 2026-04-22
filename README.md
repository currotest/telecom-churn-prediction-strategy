# telecom-churn-prediction-strategy
Machine Learning model to identify high-risk customers and quantify a €428k retention strategy ROI

# 🛡️ Churn Shield: Strategic Customer Retention System (566% ROI)

This project develops a commercial intelligence system for a Telecommunications provider. It identifies high-risk customers and quantifies the financial impact of a targeted rescue strategy.

## 📈 Business Impact
- **At-Risk Population Identified:** 1,914 customers (optimized at 0.4 threshold).
- **Protected Annual Revenue:** €566,215.
- **Estimated Net Profit:** **€428,262.45** (after campaign costs).
- **Efficiency:** 566% ROI (For every €1 spent, €5.66 are recovered).

## 🧠 Model Insights (Random Forest)
The analysis revealed that churn is not random. It follows a "Risk Trident":
1. **Contract Structure:** Month-to-month contracts are the strongest predictor of exit.
2. **Customer Value:** High-ticket customers (>€70/month) show a higher propensity to churn.
3. **Engagement Gaps:** The absence of referrals and additional services correlates heavily with abandonment.

## 🛠️ Tech Stack
- **Python / Pandas:** Financial data auditing and negative value cleaning.
- **Scikit-Learn:** Random Forest training and custom decision threshold optimization.
- **Plotly:** Interactive visualizations (Sankey Diagrams and Decision Matrices).
- **SHAP:** Model explainability (Translucent AI).

---
*Note: The model has been optimized with a 40% decision threshold to maximize the capture of critical revenue, prioritizing Recall over standard Accuracy.*
