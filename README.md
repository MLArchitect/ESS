# Predicting Subjective Well-Being (Happiness) with Machine Learning
A Minority Class Detection Approach Using European Social Survey Data

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

**Process**:

Data understanding: Used a large dataset (40,156 observations) from the European Social Survey (ESS) with 34 features on well-being, health, trust, and socio-economic factors.

Data preparation: Cleaned and preprocessed categorical and numerical variables; addressed missing values and outliers.

Feature encoding: Applied label encoding for categorical features to make them suitable for machine learning models.

Handling imbalance: Used  SMOTE  to balance the “happy” and “unhappy” classes.

Modeling: Built and compared Logistic Regression, Random Forest, LightGBM, and XGBoost classifiers to predict subjective well-being.

Evaluation: Achieved an average F1-score of 87%, with Random Forest performing best (F1: 89%, Recall: 87% for the “unhappy” class).

Interpretability: Applied SHAP and LIME to explain model predictions and identify the most influential features.

Key insights: Factors like life satisfaction, health status, loneliness, sadness, and trust in police were the strongest predictors of happiness.

Outcome: Delivered an accurate and interpretable model that can help policymakers and researchers understand the drivers of happiness and design data-driven well-being strategies.

Best Model: Random Forest
F1-score (overall): 89%
Recall (Unhappy class): 87%
Top predictive features: life satisfaction, health, loneliness, sadness, and trust in police
SHAP analysis confirmed the positive influence of "favorable" values across all features

Impact:
This project demonstrates that ML can effectively identify individuals with lower well-being, supporting public policy and intervention planning. The focus on detecting minority (unhappy) groups makes it directly relevant to fields like fraud detection, risk analysis, and anomaly detection.

Goal: Predict people’s happiness levels (subjective well-being) and identify the key factors that influence them using survey data.


