# AI-Driven-Predictive-Modeling-for-Banking-Customer-Churn-Insights-for-the-US-Financial-Sector

## Project Overview
This project aims to predict customer churn for a banking institution using machine learning techniques. Customer churn refers to the phenomenon where customers stop doing business with a company. Accurately predicting churn enables banks to implement targeted retention strategies, improve customer satisfaction, and reduce revenue loss.

The dataset contains detailed information about 10,000 customers, including demographic, account, and transactional features. Using this data, we explore various preprocessing techniques, data visualizations, and three machine learning models: Logistic Regression, Random Forest, and XGBoost.

---

## Key Features

### **Data Preprocessing**
- Handled missing values and outliers to ensure data quality.
- Encoded categorical variables (e.g., Geography, Gender) for compatibility with machine learning algorithms.
- Scaled numerical features (e.g., CreditScore, Balance, EstimatedSalary) for improved model performance.

### **Exploratory Data Analysis (EDA)**
- Visualized key patterns such as customer demographics, account features, and their correlation with churn.
- Identified influential features like Age, Balance, and IsActiveMember status.

### **Machine Learning Models**
- **Logistic Regression**: A baseline linear model.
- **Random Forest**: An ensemble model that improves accuracy and reduces overfitting.
- **XGBoost**: A gradient boosting algorithm providing state-of-the-art predictive performance.

### **Model Evaluation**
- Compared models using Accuracy, Confusion Matrix, and Classification Report.
- Highlighted the trade-offs between precision and recall for churn prediction.

---

## Model Results

### **Random Forest**
- **Accuracy**: 86.35%  
- **Confusion Matrix**:
  ```
  [[1545   62]
   [ 211  182]]
  ```
- **Classification Report**:
  ```
                precision    recall  f1-score   support

            0       0.88      0.96      0.92      1607
            1       0.75      0.46      0.57       393

     accuracy                           0.86      2000
    macro avg       0.81      0.71      0.75      2000
 weighted avg       0.85      0.86      0.85      2000
  ```

### **XGBoost**
- **Accuracy**: 86.25%  
- **Confusion Matrix**:
  ```
  [[1523   84]
   [ 191  202]]
  ```
- **Classification Report**:
  ```
                precision    recall  f1-score   support

            0       0.89      0.95      0.92      1607
            1       0.71      0.51      0.59       393

     accuracy                           0.86      2000
    macro avg       0.80      0.73      0.76      2000
 weighted avg       0.85      0.86      0.85      2000
  ```

### **Logistic Regression**
- **Accuracy**: 81.10%  
- **Confusion Matrix**:
  ```
  [[1543   64]
   [ 314   79]]
  ```
- **Classification Report**:
  ```
                precision    recall  f1-score   support

            0       0.83      0.96      0.89      1607
            1       0.55      0.20      0.29       393

     accuracy                           0.81      2000
    macro avg       0.69      0.58      0.59      2000
 weighted avg       0.78      0.81      0.77      2000
  ```

---

## Business Insights

1. **High-Risk Age Groups**:
   - Customers in the middle-age bracket (40–50 years) are more likely to churn, possibly due to financial and lifestyle changes.

2. **Account Balance Impacts Churn**:
   - Customers with zero or very low balances show a higher tendency to leave. This indicates a need to engage these customers with better incentives or personalized financial products.

3. **Activity Levels and Churn**:
   - Inactive members are significantly more likely to churn. Promoting engagement through rewards or tailored banking services can help retain these customers.

4. **Geographical Trends**:
   - Different churn rates in countries highlight potential cultural or economic factors. Banks should consider localized strategies for customer retention.

---

## Conclusion
This project demonstrates the power of machine learning in solving real-world business problems like customer churn. By leveraging advanced algorithms and data insights, banks can enhance customer satisfaction, optimize marketing budgets, and reduce churn rates effectively.

---
