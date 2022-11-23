# Customer-Churn-Prediction
**Customer Churn Prediction model created based on Classification algorithms** created with reference to **DataTalks.Club mlzoomcamp** course created using Google Colab


**Dataset**: https://raw.githubusercontent.com/alexeygrigorev/mlbookcamp-code/master/chapter-03-churn-prediction/WA_Fn-UseC_-Telco-Customer-Churn.csv

# 1. **Data Preparation**

Reading the data from csv file and checking for null values and examining important features.
      
# 2. **Exploratory Data Analysis**

* Examining important features using **mutual information(MI)** scores.
* Changing categorial variables to numerical variables using one hot encoding and pandas dummy 
* Checking correlation with numerical variables
      
# 3. **Model**

| Models        |
| -------------             |
| Logistic Regression | 
| Random Forest classifier | 
| XGB classifier          |

 Picking the best model based on maximum **Accuracy**
 
 Predicting the customer churn using the final model with test data
