# Credit-Card-Customer-Attrition-Prediction

## Project Preview

![Project Screenshot](./images/Screenshot1 (1).png)

---

# Description

This project is a **Machine Learning-based Bank Customer Churn Prediction System** developed using **Python** and **Scikit-learn** to predict whether a customer is likely to leave the bank (churn) based on demographic, account, and transaction-related information.

The project follows a complete machine learning workflow, including **data preprocessing, exploratory data analysis (EDA), feature engineering, handling class imbalance using SMOTE, model training, hyperparameter tuning, model evaluation, and feature importance analysis**. Multiple classification algorithms are trained and compared to identify the best-performing model.

---

# Features

- End-to-end Machine Learning pipeline
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Label Encoding for categorical features
- Handling missing values
- Train-Test Split
- Class imbalance handling using **SMOTE**
- Hyperparameter tuning using **GridSearchCV**
- Multiple classification models comparison
- Cross-validation
- Model evaluation using multiple metrics
- Confusion Matrix visualization
- Feature Importance analysis
- Best model selection

---

# Tech Stack

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

# Dataset

- **Dataset:** Bank Customer Churn Dataset
- **Records:** 10,127 Customers
- **Features:** 23 Attributes
- **Target Variable:** `Attrition_Flag`

The dataset contains customer demographic information, account details, transaction history, credit utilization, and relationship metrics used to predict customer churn.

---

# Project Structure

```text
Bank-Customer-Churn-Prediction/
│
├── Topic.ipynb
├── dataset/
│   └── BankChurners.csv
├── outputs/
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── evaluation_results.png
├── models/
│   └── best_model.pkl
└── README.md
```

---

# Machine Learning Pipeline

1. Import required libraries
2. Load and inspect dataset
3. Perform Exploratory Data Analysis (EDA)
4. Data Cleaning
5. Encode categorical variables
6. Feature Selection
7. Train-Test Split
8. Handle class imbalance using **SMOTE**
9. Train multiple ML models
10. Hyperparameter tuning using GridSearchCV
11. Cross-validation
12. Model evaluation
13. Compare model performance
14. Select and save the best model

---

# Models Used

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

---

# Model Performance

After hyperparameter tuning and cross-validation:

| Model | Best Cross Validation F1 Score |
|--------|-------------------------------:|
| Decision Tree | **95.08%** |
| Random Forest | **97.54%** ⭐ |
| XGBoost | **97.18%** |

### 🏆 Best Model

**Random Forest Classifier**

---

# Final Test Performance

| Metric | Score |
|---------|-------|
| Accuracy | **96.00%** |
| Precision | **97%** |
| Recall | **98%** |
| F1 Score | **96% (Weighted)** |

The Random Forest model achieved **96% test accuracy** while maintaining excellent precision and recall, making it highly effective for customer churn prediction.

![Confusion_Matrix Screenshot](./images/Screenshot1 (3).png)

---

# Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Cross Validation Score
- Confusion Matrix
- Classification Report

---

# Key Techniques Used

- Exploratory Data Analysis (EDA)
- Label Encoding
- Feature Engineering
- SMOTE (Synthetic Minority Oversampling Technique)
- Hyperparameter Tuning
- GridSearchCV
- Cross Validation
- Model Comparison

---

# Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/yourusername/Bank-Customer-Churn-Prediction.git
```

---

## 2. Navigate to the project

```bash
cd Bank-Customer-Churn-Prediction
```

---

## 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

---

## 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```text
Topic.ipynb
```

Run all notebook cells sequentially.

---

# Results

- Successfully predicted customer churn with **96% test accuracy**
- Compared three different machine learning algorithms
- Random Forest achieved the highest cross-validation F1 score (**97.54%**)
- Improved minority class prediction using **SMOTE**
- Reduced overfitting through cross-validation and hyperparameter tuning

---

# Future Improvements

- Deploy model using **Flask/FastAPI**
- Build an interactive dashboard using **Streamlit**
- Add SHAP for Explainable AI
- Perform feature selection using Recursive Feature Elimination (RFE)
- Experiment with CatBoost and LightGBM
- Dockerize the application
- Deploy on AWS/Azure/GCP

---

# Learning Outcomes

Through this project, I gained hands-on experience in:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Handling imbalanced datasets using SMOTE
- Feature engineering
- Hyperparameter tuning using GridSearchCV
- Cross-validation techniques
- Machine learning model comparison
- Customer churn prediction using classification algorithms
- Model evaluation using industry-standard metrics
- Selecting the best-performing machine learning model
