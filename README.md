# ESS
Predicting Subjective Well-Being (Happiness) with Machine Learning: A Minority Class Detection Approach Using European Social Survey Data

Objective:
This thesis aims to predict Subjective Well-Being (SWB), or happiness, using rich survey data and machine learning, with a specific focus on accurately detecting minority (unhappy) classes—similar in challenge to fraud detection use cases.

Dataset:
Source: European Social Survey (ESS) Round 11
Size: 40,156 entries, 34 categorical features (converted from 0–10 Likert scale responses)
Target Variable: Happiness (binary: Happy = 1, Unhappy = 0)

Methods:
Handled class imbalance through proper sampling and evaluation metrics
Applied Logistic Regression, Random Forest, LightGBM, and XGBoost
Used F1-score and recall with an emphasis on minority class detection
Model interpretability supported via SHAP and LIME

Key Results:
Best Model: Random Forest
F1-score (overall): 89%
Recall (Unhappy class): 87%
Top predictive features: life satisfaction, health, loneliness, sadness, and trust in police
SHAP analysis confirmed the pthe ositive influence of "favorable" values across all features

Impact:
This project demonstrates that ML can effectively identify individuals with lower well-being, supporting public policy and intervention planning. The focus on detecting minority (unhappy) groups makes it directly relevant to fields like fraud detection, risk analysis, and anomaly detection.
