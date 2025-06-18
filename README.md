# CrediScope
ML-powered credit risk analyzer that enables smarter loan decisions through predictive insights and a user-friendly interface.


**CrediScope** is a machine learning project designed to assess the creditworthiness of individuals using the German Credit dataset. This project includes exploratory data analysis, feature engineering, dimensionality reduction via PCA, and model training using various classification algorithms. The final model is deployed through a simple GUI built with Tkinter for real-time risk predictions.

---

## 🎯 Project Objective

- Predict the credit risk level (Good/Bad) of an individual based on demographic and financial attributes.
- Train and compare multiple classification algorithms.
- Reduce model complexity using PCA without sacrificing accuracy.
- Deploy the best-performing model through a user-friendly graphical interface.

---

## 📁 Dataset Overview

The dataset includes anonymized financial and personal information such as:

- Age  
- Sex  
- Job type  
- Housing type  
- Saving accounts  
- Checking account balance  
- Credit amount  
- Duration of loan  
- Loan purpose

> 📌 **Target variable:** Credit Risk (`Good` or `Bad`)

---

## 🧪 Machine Learning Pipeline

### ✔️ Steps Involved:

- **EDA & Visualization:** Analyzed feature distributions, correlations, and missing values.
- **Preprocessing:** Handled missing data, standardized numerical features, and encoded categorical variables.
- **Dimensionality Reduction:** Applied PCA to reduce dimensionality while preserving key variance.
- **Model Training:** Trained and evaluated multiple models:
  - Logistic Regression
  - Support Vector Classifier (SVC)
  - Random Forest Classifier
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Cross-Validation Score.
- **Deployment:** Best-performing model integrated into a desktop GUI using Tkinter.

---

## ⚙️ Tech Stack

- **Python 3**
- **Pandas, NumPy, Matplotlib, Seaborn** – Data manipulation & EDA  
- **Scikit-learn** – ML models, preprocessing, PCA  
- **Tkinter** – GUI deployment

---

## 📊 Project Structure

├── data/ 
├── notebooks/
│ └── german_credit_analysis.ipynb
└── README.md # Project documentation



## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/anunayaa/credit-risk-analyzer.git
cd credit-risk-analyzer
```

Enter customer details to get a prediction on their credit risk.

📌 Features
Clean, modular ML pipeline

Dimensionality reduction using PCA

GUI-based risk assessment

Easy to extend with new models or data

📈 Future Improvements
Integrate additional models like XGBoost or LightGBM

Convert GUI into a web app (Flask or Streamlit)

Automate hyperparameter tuning with GridSearchCV or Optuna

📬 Contact
For feedback, suggestions, or collaboration:

📧 Email: anunayarpillai@gmail.com
