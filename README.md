# 🛡️ Credit Card Fraud Detection using Machine Learning

## 📌 Overview

Credit card fraud is a growing concern in today’s digital economy, leading to financial loss and reduced trust in online payment systems. This project aims to develop an effective fraud detection system using machine learning techniques to identify and prevent fraudulent transactions while maintaining a smooth customer experience.

## 🎯 Objective

The goal is to analyze credit card transaction data to detect fraudulent activity. The system is designed to:
- Accurately classify transactions as fraudulent or legitimate
- Minimize false positives and false negatives
- Address challenges like imbalanced datasets and evolving fraud patterns
- Compare and evaluate multiple machine learning models

---

## 📊 Dataset

- **Total Transactions:** 100,000  
- **Total Features:** 16  
- **Target Variable:** `Fraud` (0 = Legitimate, 1 = Fraudulent)

### 🔑 Key Features:
- `Transaction ID`, `Date and Time`, `Type of Card`, `Entry Mode`, `Amount`, `Type of Transaction`, `Merchant Group`, `Country of Transaction`, `Demographics`  
- Mixture of transactional, geographical, and demographic data

---

## 🛠️ Tools & Technologies

- **Language:** Python  
- **Libraries:**  
  - `pandas` – data manipulation  
  - `numpy` – numerical computation  
  - `matplotlib` & `seaborn` – data visualization  
  - `scikit-learn` – machine learning modeling  

---

## 🤖 Machine Learning Models Used

1. **Random Forest** – Ensemble of decision trees
2. **Gradient Boosting** – Boosted trees for enhanced accuracy
3. **Support Vector Machine (SVM)** – Optimal boundary for classification
4. **Naive Bayes** – Probabilistic classifier based on Bayes' theorem
5. **K-Nearest Neighbors (KNN)** – Instance-based classification

Each model was evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

---

## 📈 Challenges Addressed

- **Imbalanced Dataset:** Used resampling and class weighting
- **False Positives/Negatives:** Balanced precision and recall
- **Adaptive Fraud Techniques:** Model tuning and retraining

---

## ✅ Outcomes

- Built and tested multiple machine learning models
- Compared performance to choose the best model
- Achieved a balance between fraud detection and customer experience

---

