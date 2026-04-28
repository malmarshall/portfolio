# Project 1 - Customer Churn Prediction (General ML Project)
#### Dataset: Telco Customer Churn (Kaggle)


## Goal: Build a machine learning model that predicts whether a customer will churn based on demographics, services, and billing behavior. 

# Outline
1. Problem definition
   - What is churn?
   - Why does it matter?
   - What business decisions can this model support?
3. Data Understanding
   - Load dataset
   - Explore:
       - Churn rate
       - Service types
       - Contract types
       - Payment methods
       - Tenure distribution
5. Data Cleaning
   - Handle missing values
   - Convert categorical variables
   - Fix data types
   - Remove duplicates
7. Feature Engineering
   - Create new features:
       - Tenure groups
       - Total services count
       - Monthly vs. Total charges ratio
    - Encode categorical variables (OneHotEncoder)
9. Modeling
    - Train/test split
    - Compare models:
        - Logistic Regression
        - Random Forest
        - XGBoost
    - Evaluate with:
        - ROC-AUC
        - Precision/Recall
        - Confusion matrix
11. Explainability
    - SHAP values
    - Feature importance
    - Partical dependence plots
13. Deployment (Optional)
    - Build a Streamlit app:
      - User inputs customer attributes
      - Model predicts churn probability


## Deliverables:
- Notebook
- README
- Model performance plots
- Optional Streamlit app
