📊 Telco Customer Churn Prediction (Machine Learning Project)
🧠 Project Overview

Customer churn is a major challenge for telecom companies.
This project predicts whether a customer will leave the service (churn) using machine learning techniques on a real-world telecom dataset.

The project demonstrates a complete ML pipeline including:

Data cleaning

Exploratory Data Analysis (EDA)

Feature engineering

Baseline model

Improved model

Model comparison

Error analysis

This notebook was implemented in Google Colab and prepared for academic submission.

🎯 Objective

To build a machine learning model that predicts whether a telecom customer will churn based on demographic, billing, and service usage features.

🗂 Dataset

Dataset: Telco Customer Churn Dataset
Contains:

Customer demographics

Contract details

Billing information

Service subscriptions

Churn label (Yes/No)

Target variable:

Churn (1 = Yes, 0 = No)

⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

🔎 Project Workflow
1. Data Cleaning

Removed unnecessary columns (customerID)

Converted TotalCharges to numeric

Handled missing values

Encoded target variable

2. Exploratory Data Analysis

EDA was performed to understand patterns affecting churn:

Contract type vs churn

Monthly charges vs churn

Tenure distribution

Churn class distribution

Key insight:
Customers with month-to-month contracts and higher monthly charges are more likely to churn.

🤖 Models Used
Baseline Model

Logistic Regression

Used as baseline classifier

Requires feature scaling

Interpretable results

Improved Model

Random Forest Classifier

Handles non-linear relationships

Captures feature interactions

Higher accuracy than baseline

📈 Model Performance
Model	Accuracy
Logistic Regression	~80%
Random Forest	~84–86%

Random Forest outperformed Logistic Regression in predicting churn.

📊 Evaluation Metrics

Accuracy

Confusion Matrix

Classification Report

Feature Importance

Confusion matrix was used to analyze:

False positives

False negatives

Overall prediction quality

⭐ Feature Importance

Top factors influencing churn:

Contract type

Monthly charges

Tenure

Internet service type

These features play a significant role in customer retention.

🧪 Error Analysis

Some churn cases were misclassified due to:

Class imbalance

Overlapping customer behavior patterns

Possible improvements:

SMOTE for class balancing

Hyperparameter tuning

XGBoost model

Cross-validation

📌 Conclusion

This project successfully built a machine learning model to predict telecom customer churn.

Key findings:

Contract type and monthly charges strongly influence churn

Random Forest performed better than Logistic Regression

Proper preprocessing and EDA significantly improve model performance

This project demonstrates a complete end-to-end machine learning workflow suitable for academic and practical applications.

▶️ How to Run

Open the notebook in Google Colab

Upload dataset CSV

Run all cells

View results and visualizations

📁 Repository Structure
telco-churn-ml/
│
├── Telco_Churn_Project.ipynb
└── README.md

👨‍💻 Author

Krishna Aggarwal
Machine Learning Project Submission

📎 Submission Note

This project was created as part of a machine learning assignment requiring:

Data cleaning

EDA

Baseline model

Improved model

Error analysis

GitHub submission
