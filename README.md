# 🏥 Hospital Readmission Prediction (Machine Learning Project)

Academic group project for the **Machine Learning (2023/24)** course.  
The goal was to build predictive models to analyse and forecast **hospital readmissions** of diabetic patients, addressing one of the most critical challenges in healthcare: **reducing rehospitalisation rates**.

## Objectives
1. **Binary Classification** – Predict if a patient will be readmitted within **30 days** of discharge.  
2. **Multiclass Classification** – Predict the timeframe of readmission:  
   - `No` (not readmitted)  
   - `<30 days`  
   - `>30 days`

Accurate predictions can help healthcare providers improve patient outcomes, reduce costs, and optimise hospital resource allocation.

## Dataset
- **Training set**: 71,236 encounters, 31 features  
- **Test set**: 30,530 encounters  
- Features include demographics, hospital visits, medical exams, diagnoses, medications, and discharge details.  
- Targets:  
  - `readmitted_binary`  
  - `readmitted_multiclass`

## Data Preprocessing
- Handling missing values and outliers  
- Feature engineering:  
  - New variables and simplified categorical variables
- Feature selection 
- Data balancing 
- Scaling 

## Models & Approach
- Algorithms tested: Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, KNN, Naïve Bayes, Neural Networks (MLP)  
- Evaluation metrics: **Accuracy, Precision, Recall, F1 Score, ROC-AUC**  
- Model selection via **GridSearchCV** and **RandomizedSearchCV**  
- Ensemble methods applied: **Bagging, Random Forest, Gradient Boosting, AdaBoost, Stacking Classifier**  

## Results
- **Binary classification**:  
  - Best overall model → **Random Forest**
- **Multiclass classification**:  
  - Best model → **Random Forest** 
- Ensemble methods (Random Forest, Gradient Boosting) consistently outperformed baseline models.

## Learnings
- Preprocessing and feature engineering had major impact on model performance.  
- Balancing strategies (SMOTE vs undersampling) significantly influenced results.  
- Random Forest proved robust in both binary and multiclass settings.  
- Computational constraints limited exhaustive hyperparameter tuning.  

## Team
Group 08 – Machine Learning 2023/24
