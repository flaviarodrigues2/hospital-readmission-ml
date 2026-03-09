# Hospital Readmission Prediction (Machine Learning Project)

The goal was to build predictive models to analyse and forecast hospital readmissions of diabetic patients, addressing one of the most critical challenges in healthcare: reducing rehospitalisation rates.

## Objectives
1. Binary Classification – Predict if a patient will be readmitted within 30 days of discharge.  
2. Multiclass Classification – Predict the timeframe of readmission:  
   - `No` (not readmitted)  
   - `<30 days`  
   - `>30 days`

## Dataset
- Training set: 71,236 encounters, 31 features  
- Test set: 30,530 encounters  
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
- Evaluation metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC 
- Model selection via GridSearchCV and RandomizedSearchCV  
- Ensemble methods applied: Bagging, Random Forest, Gradient Boosting, AdaBoost, Stacking Classifier 

## Results
- Binary classification:  
  - Best overall model → Random Forest
- Multiclass classification:  
  - Best model → Random Forest
- Ensemble methods (Random Forest, Gradient Boosting) consistently outperformed baseline models.
