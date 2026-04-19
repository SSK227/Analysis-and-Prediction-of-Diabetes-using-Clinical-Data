# 🩺 Analysis and Prediction of Diabetes Using Clinical and Demographic Health Indicators

## 📌 Project Overview
This project focuses on predicting diabetes using machine learning techniques based on clinical and demographic health indicators. The dataset used is the Pima Indian Diabetes Dataset, which contains medical records of female patients.

The goal is to identify key factors influencing diabetes and build models to accurately classify patients as diabetic or non-diabetic.

---

## ❓ Research Question
Which physiological factors have the strongest influence on the likelihood of developing diabetes?

---

## 🎯 Objectives
- Understand the dataset and its structure
- Perform Exploratory Data Analysis (EDA)
- Handle missing/invalid data
- Build and evaluate machine learning models
- Identify key predictors of diabetes
- Provide meaningful insights for healthcare

---

## 📊 Dataset Information
- Source: UCI / Kaggle (Pima Indian Diabetes Dataset)
- Records: 768
- Features: 8 input features + 1 target variable
- Target: `Outcome` (0 = Non-Diabetic, 1 = Diabetic)

---

## 🧹 Data Preprocessing
- Replaced invalid zero values with NaN
- Removed missing values using `dropna()`
- Performed train-test split (80-20) using stratification
- Applied feature scaling using StandardScaler

---

## 📈 Exploratory Data Analysis (EDA)
- Pie chart for class distribution
- Histograms for feature distributions
- Boxplots (Glucose, BMI, Age, Insulin vs Outcome)
- Correlation heatmap
- Pairplot and scatter plots
- Zero-value analysis

---

## 🤖 Models Used
- Gradient Boosting
- XGBoost
- AdaBoost
- Decision Tree

---

## ⚙️ Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Curve

---

## 🏆 Results Summary
| Model              | Accuracy | Recall | F1 Score |
|-------------------|---------|--------|----------|
| AdaBoost          | 84.8%   | 73.1%  | 0.76     |
| XGBoost           | 82.3%   | 76.9%  | 0.74     |
| Gradient Boosting | 78.5%   | 61.5%  | 0.65     |
| Decision Tree     | 72.2%   | 65.4%  | 0.60     |

👉 AdaBoost performed best overall with balanced performance.

---

## 🔍 Key Findings
- **Glucose** is the most important predictor
- Followed by **BMI** and **Age**
- Ensemble methods outperform single models
- Recall is critical in medical prediction to reduce false negatives

---

## 🔧 Hyperparameter Tuning
- Used GridSearchCV with 5-fold cross-validation
- Optimized model parameters for better performance

---

## 📉 Limitations
- Dataset size reduced after cleaning
- No SMOTE used for class imbalance
- Limited generalizability (specific population)

---

## 🚀 Future Work
- Apply SMOTE for imbalance handling
- Use advanced imputation techniques (KNN)
- Try deep learning models
- Validate on larger and diverse datasets

---

## 🛠️ Technologies Used
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---


---

## 👨‍🎓 Author
**Shiva Krishna Srirama Dasu**  
MSc Data Science  
University of Hertfordshire

---

## 📎 Notes
- All code is original and developed for academic purposes
- Dataset is publicly available and anonymised
- Project report included in repository

---
