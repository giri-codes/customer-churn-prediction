# Customer Churn Prediction

This project builds a machine learning classification model to predict whether a customer will churn (leave a service) based on customer behavior and account information.

Customer churn prediction helps businesses identify customers who are likely to leave and take proactive actions to improve retention.

---

## Dataset

The dataset contains customer information including:

- Tenure
- MonthlyCharges
- TotalCharges
- Churn status

Target variable:

**Churn**
- 0 → Customer stays
- 1 → Customer leaves

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Machine Learning Workflow

The project follows a structured machine learning pipeline:

1. Import required libraries
2. Load dataset
3. Data exploration
4. Data preprocessing
5. Target variable encoding
6. Feature selection
7. Train-test split
8. Logistic Regression model training
9. Model prediction
10. Model evaluation

---

## Model Used

This project uses **Logistic Regression**, a classification algorithm used to predict the probability of a binary outcome.

In this case, the model predicts whether a customer will churn or stay.

---

## Evaluation Metrics

Model performance is evaluated using:

- Confusion Matrix
- Precision
- Recall
- F1 Score
- ROC Curve

These metrics help measure how well the model identifies customers who are likely to churn.

---

## Visualization

The project includes model evaluation visualizations such as:

- Confusion Matrix
- ROC Curve

These visualizations help interpret classification performance.

---

## Conclusion

The Logistic Regression model predicts customer churn based on customer account and usage features.

Churn prediction models help businesses identify at-risk customers and take proactive retention actions.
