# 📊 Loan Default Risk Prediction & Business Cost Optimization

## 🚀 Project Overview

This project focuses on predicting the likelihood of loan default using machine learning techniques and optimizing decision-making using a business cost framework.

In real-world financial systems, simply maximizing model accuracy is not enough. Instead, this project emphasizes minimizing financial loss by adjusting the classification threshold based on business costs.

---

## 🎯 Objective

* Predict whether a customer will default on a loan
* Optimize the classification threshold using cost-benefit analysis
* Minimize total business loss caused by incorrect predictions

---

## 🧠 Key Concepts

* **Binary Classification** (Default vs Non-default)
* **Cost-Sensitive Learning**
* **Threshold Optimization**
* **Business Decision Modeling**

---

## 📁 Dataset

The dataset contains borrower-related information such as:

* Personal details (age, income, employment length)
* Loan details (amount, interest rate, grade)
* Credit history
* Loan status (Target Variable)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* CatBoost
* Matplotlib & Seaborn

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Handled missing values
* Encoded categorical variables
* Feature scaling for Logistic Regression

### 2️⃣ Model Building

* Logistic Regression
* CatBoost Classifier

### 3️⃣ Model Evaluation

* Classification Report
* Confusion Matrix

### 4️⃣ Business Cost Optimization 💰

Defined cost values:

* False Positive (FP): High cost (approving risky loan)
* False Negative (FN): Moderate cost (rejecting good customer)

Optimized decision threshold to minimize:
Total Cost = (FP × Cost_FP) + (FN × Cost_FN)

---

## 📉 Results

* CatBoost performed better than Logistic Regression
* Threshold tuning significantly reduced business loss
* Demonstrated that optimal threshold ≠ 0.5

---

## 📊 Key Insight

Traditional ML focuses on accuracy, but in business:

> **The best model is the one that minimizes cost, not error.**

---

## 🔍 Future Improvements

* Hyperparameter tuning
* Use of advanced models (XGBoost, LightGBM)
* Deployment using Streamlit or Flask
* Real-time prediction system

---

## 💼 Business Impact

This project simulates a real banking scenario where:

* Bad loan approvals are minimized
* Profitability is improved through better decision-making
* Risk is managed more effectively

---

## 📌 How to Run

```bash
# Clone repository
git clone https://github.com/your-username/loan-default-risk.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit pull requests.

---

## 📬 Contact

For any queries or collaboration:

* LinkedIn: (https://www.linkedin.com/in/muhammad-bilal-sarwar-b5b4a4368?utm_source=share_via&utm_content=profile&utm_medium=member_android)
* Email: (bilalsarwarbilalsarwar03@gmail.com)

---

⭐ If you found this project helpful, please give it a star!
 
