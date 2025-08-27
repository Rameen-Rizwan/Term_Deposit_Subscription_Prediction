# Term Deposit Subscription Prediction

## Project Overview
This project focuses on predicting whether a bank customer will **subscribe to a term deposit** after a marketing campaign.  
It uses classification models and machine learning techniques to analyze the dataset and evaluate model performance.

---

## Objectives
- Load and preprocess the dataset  
- Perform exploratory analysis (categorical & numerical features)  
- Apply feature engineering and transformations  
- Train and evaluate multiple classification models  
- Optimize thresholds for best performance metrics  
- Explain predictions using **LIME** for interpretability  

---

## Dataset
- **Source:** Bank marketing dataset (term deposit subscription)  
- **Target Variable:** `y` (yes → 1, no → 0)  
- **Features:** Demographic & campaign-related attributes such as:
  - Age, Job, Marital Status, Education  
  - Balance, Duration, Campaign, Previous  
  - Contact type, Month, Day of week, etc.  

---

## Project Workflow
The notebook is structured into the following steps:

1. **Import Required Libraries**  
2. **Load Dataset**  
3. **Data Preprocessing**  
   - Splitting features and target  
   - Handling categorical & numerical columns  
   - Encoding & scaling  
4. **Logistic Regression**  
   - Training & evaluation  
   - Classification report & confusion matrix  
   - ROC curve  
5. **Random Forest**  
   - Training & evaluation (train/test accuracy, confusion matrix, ROC)  
   - Threshold tuning for best F1 score  
6. **Model Explainability with LIME**  
   - Instance-level feature contributions  
   - Visual & tabular explanations  

---

## Evaluation Metrics
Models are evaluated using:
- Accuracy (Train & Test)  
- Precision, Recall, F1-score  
- Confusion Matrix  
- ROC-AUC Curve  
- Optimal threshold analysis for F1 optimization  

---

## Model Explainability
- **LIME (Local Interpretable Model-agnostic Explanations)** is used to explain individual predictions.  
- Provides both **visual bar plots** and **tabular feature contributions** for transparency.  

---

## Results

- Logistic Regression and Random Forest both achieve strong performance.

- Random Forest shows higher recall and ROC-AUC.

- Threshold tuning further improves F1-score.

- LIME provides interpretability at the instance level.