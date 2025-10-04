# Titanic_survival_prediction_using_logistic_regression1
Machine Learning project predicting Titanic survival with Logistic Regression &amp; KNN — full pipeline with preprocessing, evaluation, and new data prediction.

# 🚢 Titanic Survival Prediction — Logistic Regression & KNN

This project predicts passenger survival from the famous **Titanic dataset** (Kaggle).  
It demonstrates a complete **Machine Learning pipeline** in **Google Colab** using Python, Scikit-learn, and Pandas.

🔗 Dataset: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)  
🔗 Colab/Repo: [Your Colab or GitHub Link Here]

---

## 📌 Project Overview
- **Goal:** Predict whether a passenger survived (1) or not (0).  
- **Techniques Used:** Logistic Regression (primary), KNN (comparison).  
- **Focus Concepts:** Data preprocessing, feature engineering, scaling, classification, and model evaluation.  

---

## ⚙️ Features Used
- **Pclass** → Ticket class (1st, 2nd, 3rd)  
- **Sex** → Gender of passenger  
- **Age** → Age in years  
- (Optional extras: `Fare`, `Embarked`, `FamilySize`, etc.)

**Target (y):** `Survived` → 0 = Did not survive, 1 = Survived  

---

## 🛠️ Steps in the Pipeline
1. **Import libraries** → pandas, numpy, sklearn, seaborn, matplotlib  
2. **Load data** → from Kaggle Titanic dataset (`train.csv`)  
3. **EDA** → Explore missing values & data distribution  
4. **Handle missing values** → Impute Age, Embarked, and Fare where necessary  
5. **Encode categorical features** → Convert Sex/Embarked into numeric form  
6. **Feature selection** → Drop irrelevant columns (PassengerId, Name, Ticket)  
7. **Split X and y** → Features (X) and target (y)  
8. **Train/Test split** → 80% training, 20% testing  
9. **Scale features** → StandardScaler for better model performance  
10. **Train Logistic Regression model**  
11. **Evaluate model** → Accuracy, Classification Report, Confusion Matrix, ROC-AUC  
12. **Compare with KNN** → Evaluate alternative model  
13. **Predict new passenger survival**  
14. **Save model/notebook** → For reuse & sharing  

---

## 📊 Evaluation Metrics
- **Accuracy Score**  
- **Precision, Recall, F1-score** (Classification Report)  
- **Confusion Matrix**  
- **ROC-AUC Curve**  

---

## 🚀 Results
- Logistic Regression achieved strong accuracy with balanced performance.  
- KNN provided a comparative baseline.  
- Notebook includes **predictions for new passenger data**.  

---

## 📂 Repository Structure
