# Problem
Online payment is the most popular transaction method in the world today. However, with an increase in online payments also comes a rise in payment fraud. The objective of this study is to identify fraudulent and non-fraudulent payments. The dataset is collected from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments.

# Dataset Information
The dataset consists of 10 variables:
- step: represents a unit of time where 1 step equals 1 hour
- type: type of online transaction
- amount: the amount of the transaction
- nameOrig: customer starting the transaction
- oldbalanceOrg: balance before the transaction
- newbalanceOrig: balance after the transaction
- nameDest: recipient of the transaction
- oldbalanceDest: initial balance of recipient before the transaction
- newbalanceDest: the new balance of recipient after the transaction
- isFraud: fraud transaction
  
# Approach Used
- Loaded and cleaned the dataset, handling missing values and outliers.Conducted exploratory data analysis (EDA) to 
  understand key trends and correlations.
- Balanced the dataset and Scaled numerical variables to improve model performance.
- Tested multiple machine learning models, including Logistic Regression, Decision Tree, Random Forest, and 
  XGBoost.Tuned hyperparameters for optimal performance.
- Used accuracy, precision, recall, F1-score, and AUC-ROC to assess model effectiveness.Focused on reducing false 
  negatives, as missing a potential fraudulent is more costly than misclassifying a legitimate transaction.
