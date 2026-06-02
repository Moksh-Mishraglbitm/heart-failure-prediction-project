# heart-failure-prediction-project
HEART FAILURE PREDICTION USING MACHINE LEARNING
==============================================

PROJECT OVERVIEW
----------------
This project predicts the risk of death due to heart failure using clinical patient records and Machine Learning.

The objective is to analyze patient health indicators and classify whether a patient is likely to experience a death event.

DATASET
-------
Heart Failure Clinical Records Dataset

Dataset Size:
- 299 Patient Records
- 13 Features

Features Include:
- Age
- Anaemia
- Creatinine Phosphokinase
- Diabetes
- Ejection Fraction
- High Blood Pressure
- Platelets
- Serum Creatinine
- Serum Sodium
- Sex
- Smoking
- Time
- DEATH_EVENT (Target)

TARGET VARIABLE
---------------
DEATH_EVENT

0 = Survived
1 = Death Event

TECHNOLOGIES USED
-----------------
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

PROJECT WORKFLOW
----------------
1. Load Clinical Dataset
2. Data Exploration
3. Statistical Analysis
4. Feature Correlation Analysis
5. Data Visualization
6. Train-Test Split
7. Logistic Regression Model Training
8. Prediction and Evaluation
9. ROC Curve Analysis
10. Probability-Based Prediction

EXPLORATORY DATA ANALYSIS
-------------------------
Performed:
- Dataset Information Analysis
- Summary Statistics
- Target Class Distribution
- Correlation Analysis
- Boxplots
- Heatmaps
- Feature Relationship Analysis

VISUALIZATIONS
--------------
- Class Distribution Analysis
- Correlation Heatmap
- Age vs Death Event Boxplot
- Serum Creatinine vs Death Event Boxplot
- ROC Curve

MACHINE LEARNING MODEL
----------------------
Model Used:
- Logistic Regression

MODEL EVALUATION
----------------
Metrics Used:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve
- AUC Score

RESULTS
-------
Model Accuracy:
~78%

ROC-AUC Score:
~0.83

These results indicate good predictive performance for identifying high-risk heart failure patients.

KEY FINDINGS
------------
- Higher Serum Creatinine is associated with increased mortality risk.
- Age shows a relationship with death events.
- Certain clinical features contribute more strongly to prediction.
- Logistic Regression provides interpretable predictions.

SAMPLE PREDICTION
-----------------
Input:
Patient Clinical Information

Output:
Prediction:
- Survived (0)
OR
- Death Event (1)

Probability:
Model returns prediction confidence score.

SKILLS DEMONSTRATED
-------------------
- Data Analysis
- Data Visualization
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Classification
- Logistic Regression
- Model Evaluation
- ROC-AUC Analysis
- Healthcare Analytics

AUTHOR
------
Moksh Mishra

STATUS
------
Completed
