# AI-Driven-Predictive-Modeling-for-Banking-Customer-Churn-Insights-for-the-US-Financial-Sector

## Project Overview
This project focuses on predicting customer churn for a banking institution using machine learning models. Customer churn, the rate at which customers stop doing business with a company, is a critical metric for understanding customer retention and improving business strategies. By analyzing the dataset and applying classification models, we aim to provide actionable insights and accurate predictions to assist the bank in retaining its customers.

---

## Dataset Description
The dataset contains 10,000 observations with the following features:

- **RowNumber**: Index of the row.
- **CustomerId**: Unique identifier for the customer.
- **Surname**: Customer's surname.
- **CreditScore**: Credit score of the customer.
- **Geography**: Country of residence.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Tenure**: Number of years the customer has been with the bank.
- **Balance**: Account balance of the customer.
- **NumOfProducts**: Number of bank products used by the customer.
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No).
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No).
- **EstimatedSalary**: Estimated annual salary of the customer.
- **Exited**: Whether the customer churned (1 = Yes, 0 = No).

---

## Data Preprocessing
The dataset underwent the following preprocessing steps:

1. **Handling Missing Values**: Ensured no missing values were present.
2. **Encoding Categorical Variables**: Used one-hot encoding for `Geography` and label encoding for `Gender`.
3. **Feature Scaling**: Applied MinMaxScaler to normalize features.
4. **Feature Selection**: Removed non-informative columns such as `RowNumber`, `CustomerId`, and `Surname`.
5. **Splitting the Dataset**: Split into training and testing sets (80%-20%).

---

## Models Applied
Three machine learning models were applied to predict customer churn:

### 1. Logistic Regression
- **Accuracy**: 81.1%
- **Classification Report**:
  - Precision (Class 0): 0.83
  - Recall (Class 0): 0.96
  - F1-Score (Class 0): 0.89
  - Precision (Class 1): 0.55
  - Recall (Class 1): 0.20
  - F1-Score (Class 1): 0.29

### 2. Random Forest
- **Accuracy**: 86.35%
- **Classification Report**:
  - Precision (Class 0): 0.88
  - Recall (Class 0): 0.96
  - F1-Score (Class 0): 0.92
  - Precision (Class 1): 0.75
  - Recall (Class 1): 0.46
  - F1-Score (Class 1): 0.57

### 3. XGBoost
- **Accuracy**: 86.25%
- **Classification Report**:
  - Precision (Class 0): 0.89
  - Recall (Class 0): 0.95
  - F1-Score (Class 0): 0.92
  - Precision (Class 1): 0.71
  - Recall (Class 1): 0.51
  - F1-Score (Class 1): 0.59

---

## Business Insights
- The **Random Forest model** provided the highest accuracy and balanced performance, making it the best choice for predicting customer churn.
- Customers with higher credit scores and active memberships are less likely to churn.
- Understanding churn drivers, such as balance levels and tenure, can help the bank design targeted retention strategies.

---

## Conclusion
This project successfully predicts customer churn using advanced machine learning techniques. The insights derived can guide banks in improving customer retention, enhancing profitability, and refining their business strategies.

