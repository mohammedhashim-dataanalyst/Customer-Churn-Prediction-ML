# 📊 Customer Churn Prediction (Machine Learning)

## 📌 Project Overview
This project predicts telecom customer churn using Machine Learning.  
The goal is to identify customers who are likely to leave the company, allowing businesses to take preventive action.

The model was built using **Logistic Regression** and evaluated using multiple performance metrics.

---

## 📁 Dataset
- Telco Customer Churn Dataset (Kaggle)
- Total Records: 7,043 customers
- Features: Demographics, Account Information, Services, Billing Details
- Target Variable: `Churn` (Yes/No)

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Removed unnecessary columns
- Converted `TotalCharges` to numeric
- Handled missing values
- Encoded categorical variables using One-Hot Encoding

### 2️⃣ Feature Engineering
- Separated features (X) and target (y)
- Applied StandardScaler to normalize data

### 3️⃣ Model Training
- Train-Test Split (80/20)
- Logistic Regression model trained on training data

### 4️⃣ Model Evaluation
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve
- AUC Score
- Feature Importance Analysis

---

## 📈 Model Performance

- **Accuracy:** 82%
- **ROC-AUC Score:** 0.86
- **Precision (Churn):** 0.68
- **Recall (Churn):** 0.60
- **F1-Score (Churn):** 0.64

---

## 🔍 Key Insights

### 🚨 Factors Increasing Churn
- Fiber Optic Internet Service
- High Total Charges
- Month-to-Month Contracts
- Electronic Check Payment Method

### 🟢 Factors Reducing Churn
- Long Customer Tenure
- Two-Year Contracts
- One-Year Contracts
- Online Security
- Tech Support Services

---

## 💡 Business Recommendations

- Encourage long-term contracts through discounts
- Improve Fiber Optic service experience
- Focus on early customer retention strategies
- Bundle Tech Support and Online Security services

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure
Customer-Churn-Prediction-ML/

│

 ├── data/

│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv

│

 ├── notebooks/

│ └── churn_model.ipynb

│

 ├── requirements.txt

 └── README.md

---

## 🚀 Future Improvements

- Implement Random Forest & XGBoost
- Hyperparameter tuning
- Handle class imbalance using SMOTE
- Deploy using Streamlit

---

## 👤 Author
Mohammed Hashim
---

⭐ If you found this project helpful, feel free to star the repository!
