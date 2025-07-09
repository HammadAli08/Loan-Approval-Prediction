# 🏦 Loan Approval Prediction System

This project is a machine learning solution that predicts whether a loan application will be approved or not based on applicant details such as income, assets, credit history, and other relevant factors.

---

## 📌 Overview

The goal of this project is to build a classification model using Python that helps automate the decision-making process in loan approvals. The model is trained on a real-world dataset and evaluated using standard metrics to ensure reliability.

---

## 🚀 Tools & Technologies

- **Python**
- **Pandas & NumPy** – data cleaning and manipulation  
- **Matplotlib & Seaborn** – data visualization  
- **Scikit-learn** – model building and evaluation  
- **Jupyter Notebook**

---

## 📂 Dataset

- Source: [Kaggle – Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- Features include:
  - `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Credit_History`, etc.
- Target variable: `Loan_Status` (Y/N)

---

## 📊 Project Workflow

1. **Data Preprocessing**  
   - Handled missing values  
   - Encoded categorical variables  
   - Created new features (e.g., total income, loan-to-income ratio)

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions and feature-target relationships  
   - Checked correlations and outliers

3. **Model Building**  
   - Tried Logistic Regression, Random Forest, and Decision Tree classifiers  
   - Tuned hyperparameters for better performance

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision & Recall  
   - Confusion Matrix  
   - ROC-AUC

---

## 📈 Results

- Best model accuracy: **85%**
- ROC-AUC Score: **~0.90**
- Random Forest performed the best in terms of overall balance

---

## 🧠 Key Learnings

- Feature engineering greatly impacts model accuracy  
- Balancing the dataset can improve results  
- Logistic Regression is interpretable but sometimes underperforms vs ensemble models

---

## 💡 Future Improvements

- Deploy using **Streamlit** for interactive predictions  
- Improve model with advanced techniques (XGBoost, SMOTE, pipeline handling)
- Integrate with a SQL database for real-time data

---

## 📬 Contact

**Hammad Ali Tahir**  
Feel free to connect on LinkedIn or check out more of my work on GitHub!

