Capstone Project: Pregnancy Drug Safety Prediction

Project Overview:
This project applies AI and machine learning to classify medications as safe, caution, or unsafe during pregnancy. It combines structured drug data and text-based information from clinical notes and drug descriptions to create robust predictive models.

Key Features:

Data Sources: FDA drug safety datasets, clinical trial reports, drug labeling information.
Tech Stack: Python (pandas, scikit-learn, XGBoost, imbalanced-learn), Jupyter Notebook, NumPy, Matplotlib, Seaborn, SciSpaCy (NLP tokenization), SHAP (explainable AI).
Analysis & Modeling:
Tokenized drug descriptions using NLP to extract semantic features.
Handled class imbalance using SMOTE to oversample minority safety categories.
Built classification models (XGBoost, Random Forest) to predict safety categories.
Evaluated models with Accuracy, Precision, Recall, F1-Score, and AUC-ROC.
Applied SHAP values to explain model predictions and identify key risk factors.
Visualizations:
SHAP feature importance plots.
Safety trend charts across drug categories.
Interactive visualizations for model interpretability.

Impact:

Helps healthcare providers make informed decisions about medication prescriptions during pregnancy.
Empowers expecting mothers with evidence-based guidance.
Demonstrates advanced AI techniques in health data science, including imbalanced data handling and explainable ML.
