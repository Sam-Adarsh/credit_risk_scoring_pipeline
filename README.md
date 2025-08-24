# 📊 Credit Risk Scoring Pipeline  

An **end-to-end machine learning pipeline** for credit risk scoring using the **German Credit Dataset (OpenML id=31)**.  
This project demonstrates how to build, evaluate, and persist a production-ready model for financial risk assessment.  

---

## 🔎 Overview  
- Loads dataset directly from **OpenML**.  
- Preprocesses numerical & categorical features (imputation, scaling, one-hot encoding).  
- Trains a **Gradient Boosting Classifier** using scikit-learn.  
- Evaluates with **accuracy, ROC-AUC, confusion matrix, and classification report**.  
- Saves the trained pipeline for reuse with `joblib`.  

---

## ⚙️ Tech Stack  
- Python 3.9+  
- scikit-learn  
- numpy, pandas  
- matplotlib  
- joblib  

---
