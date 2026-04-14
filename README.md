# Breast Cancer ML Pipeline

This project focuses on building a complete supervised machine learning pipeline using the Breast Cancer Wisconsin dataset. The goal was to understand how raw data can be processed and used to train different models for classification.

---

## 📌 Project Overview

In this project, I worked on:
- Data preprocessing and cleaning  
- Feature scaling  
- Training multiple machine learning models  
- Comparing model performance  

The dataset is used to classify tumors as **malignant (1)** or **benign (0)**.

---

## ⚙️ Models Used

The following models were implemented and compared:

- Logistic Regression  
- Decision Tree  
- k-Nearest Neighbors (kNN)  
- Random Forest  
- Gradient Boosting  

---

## 📊 Results

| Model               | Accuracy | F1 Score |
|--------------------|----------|----------|
| Logistic Regression | 97.37%   | 0.9647   |
| Decision Tree       | 93.85%   | 0.9157   |
| kNN (k=9)           | 96.49%   | 0.9535   |
| Random Forest       | 96.49%   | 0.9524   |
| Gradient Boosting   | 95.61%   | 0.9412   |

👉 Logistic Regression performed the best on this dataset.

---

## 🔍 Key Observations

- Logistic Regression worked very well because the dataset is close to linearly separable.  
- Decision Tree was the easiest to interpret due to clear decision rules.  
- kNN required proper feature scaling to perform well.  
- Ensemble models gave strong results but did not outperform Logistic Regression in this case.  

---

## 🧠 What I Learned

- Preprocessing steps like scaling can significantly impact model performance  
- Simpler models can sometimes outperform more complex ones  
- Choosing the right evaluation metric is important (not just accuracy)  
- Different models behave differently on the same dataset  

---

## 📁 Files Included

- `breast cancer.ipynb` → Complete implementation  
- `report.pdf` → Detailed explanation and analysis  

---

## 🚀 Future Improvements

- Try hyperparameter tuning using GridSearchCV  
- Add cross-validation  
- Test on other medical datasets  

---

## 📌 Dataset

Breast Cancer Wisconsin Dataset (UCI / Kaggle)

---

## ⭐ Final Note

This project was done as part of a machine learning assignment to understand end-to-end model building and evaluation.
