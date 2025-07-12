
# 📊 Customer Churn Prediction - Telco Dataset

This project performs exploratory data analysis and builds a machine learning model to predict customer churn in a telecommunications company. The goal is to identify customers who are likely to leave the service, allowing the company to take preventive actions.

---

## 📁 Dataset

The dataset used is the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), which contains real anonymized customer data such as:

- Demographics (gender, age, etc.)
- Account information (contract type, tenure, charges)
- Services subscribed (Internet, Phone, Streaming, etc.)

---

## 🔍 Exploratory Data Analysis (EDA)

- Removed missing values from `TotalCharges`
- Converted categorical columns using `LabelEncoder`
- Performed Chi-square tests to assess relationship between categorical features and Churn
- Analyzed correlations with numeric features like `tenure`, `MonthlyCharges`, and `TotalCharges`
- Plotted churn distribution and Chi-square p-values for categorical features

---

## 🧠 Model Training

- Model used: `LogisticRegression` from scikit-learn
- Split into training and test sets (70/30)
- Trained on all features (after preprocessing)
- Evaluation metrics:
  - Accuracy
  - Confusion Matrix
  - Classification Report (precision, recall, F1-score)

---

## 🧪 Example: Predicting Churn for a New Customer

An example is included at the end of the script where a new customer’s data (already encoded) is passed to the model for churn prediction.

---

## 📌 Notes

- This is an introductory project built during my **second month** of studying Data Science.
- I'm sharing this as part of my learning journey.
- Connect with me on LinkedIn: [Lucas Diagone](https://www.linkedin.com/in/lucas-diagone-691285104/)

---

## ⚙️ Tech Stack

- Python
- Pandas, NumPy, Seaborn, Matplotlib
- scikit-learn (preprocessing, modeling, evaluation)
