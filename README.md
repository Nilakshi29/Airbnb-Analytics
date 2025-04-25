# 📊 Loan Classification - Machine Learning Models

This project explores and implements multiple machine learning models to classify whether a loan is **paid off** or **in collection** using historical loan data.

## 📁 Dataset

The dataset used in this project is `loan_train.csv`, which contains details of 346 customers, including:

- **Loan Status**: Target variable (`PAIDOFF` or `COLLECTION`)
- **Principal**: Loan amount
- **Terms**: Weekly, Biweekly, or Monthly
- **Effective Date**: Loan start date
- **Due Date**: Loan due date
- **Age**: Applicant’s age
- **Education**: Education level of applicant
- **Gender**: Gender of applicant

## 🔍 Exploratory Data Analysis (EDA)

Performed the following EDA steps:
- Shape of the dataset (rows & columns)
- Missing values check
- Outlier detection
- Distribution plots (e.g., Principal, Age)
- KDE curves for distribution insights
- Count plots for categorical features
- Feature engineering (e.g., extracting day of week from dates)

## 🧠 Machine Learning Models

Trained and evaluated the following classification models:

| Model                   | Accuracy |
|------------------------|----------|
| Logistic Regression     | 1.0000   |
| Naive Bayes             | 0.9857   |
| Decision Tree           | 1.0000   |
| Support Vector Machine  | 1.0000   |
| K-Nearest Neighbors     | 0.9429   |

### 📌 Evaluation Metrics:
- Confusion Matrix
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)

## 🛠️ Tech Stack

- Python 🐍
- Pandas & NumPy
- Seaborn & Matplotlib (for visualization)
- Scikit-learn (model training and evaluation)
- Machine Learning Models

