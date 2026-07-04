# 💳 Credit Scoring Model using Machine Learning

## 📌 Project Overview

The Credit Scoring Model predicts an individual's creditworthiness using historical financial data. By analyzing factors such as income, debt, credit score, payment history, and financial assets, the model classifies customers as creditworthy or non-creditworthy. This project demonstrates the application of machine learning algorithms in financial risk assessment.

---

## 🎯 Objective

Build a machine learning classification model to predict an individual's creditworthiness using historical financial data and compare the performance of different classification algorithms.

---

## 🚀 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering using financial attributes
- Creditworthiness prediction
- Comparison of multiple machine learning models
- Model evaluation using classification metrics
- Feature importance analysis
- Confusion Matrix and ROC Curve visualization

---

## 📂 Dataset

The dataset contains customer financial information such as:

- Age
- Annual Income
- Credit Score
- Loan Amount
- Monthly Debt Payments
- Debt-to-Income Ratio
- Payment History
- Previous Loan Defaults
- Savings Account Balance
- Total Assets
- Total Liabilities
- Net Worth

### Target Variable

- **Creditworthy**
  - **1** → Creditworthy
  - **0** → Not Creditworthy

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🤖 Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Feature Engineering

Important financial features used for prediction include:

- Annual Income
- Credit Score
- Debt-to-Income Ratio
- Payment History
- Previous Loan Defaults
- Total Assets
- Total Liabilities
- Net Worth

---

## 📁 Project Structure

```
Credit-Scoring-Model/
│
├── Dataset/
├── notebooks/
├── images/
├── credit_scoring_model.ipynb
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/Credit-Scoring-Model.git
```

### Navigate to the project folder

```bash
cd Credit-Scoring-Model
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Launch the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
credit_scoring_model.ipynb
```

Run all cells to preprocess the data, train the models, and evaluate their performance.

---

## 📈 Model Evaluation

The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

These metrics help assess how effectively the model identifies creditworthy and non-creditworthy applicants.

---

## 📊 Project Workflow

```
Financial Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
(Logistic Regression,
Decision Tree,
Random Forest)
        │
        ▼
Model Evaluation
        │
        ▼
Creditworthiness Prediction
```

---

## 📊 Model Comparison

The project compares the performance of multiple classification algorithms using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

The best-performing model is selected based on these evaluation metrics.

---

## 📌 Key Insights

- Credit Score is one of the strongest indicators of creditworthiness.
- Customers with higher Debt-to-Income Ratios generally have a higher credit risk.
- Payment History significantly influences loan approval decisions.
- Random Forest generally provides better predictive performance than a single Decision Tree due to reduced overfitting.
- Comparing multiple models helps identify the most reliable approach for credit scoring.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation for robust model evaluation
- Model deployment using Flask or Streamlit
- Explainable AI using SHAP or LIME
- Real-time credit scoring application

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, improve the project, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Aditya Vikram Singh**

Machine Learning | Data Science | Artificial Intelligence Enthusiast

⭐ If you found this project useful, consider giving it a star on GitHub!
