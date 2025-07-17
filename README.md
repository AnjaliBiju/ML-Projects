# ML Projects

This repository contains multiple Machine Learning projects demonstrating the application of various algorithms on real-world datasets.

---

## 1. Predicting Advertisement Clicks using User Behavior Data

This project focuses on **predicting user ad-click behavior** based on demographic and usage data using **Logistic Regression**, a widely used classification algorithm.

### 📊 Dataset Highlights
- Features: `Daily Time Spent on Site`, `Age`, `Area Income`, `Daily Internet Usage`, `Gender`
- Target: `Ad Click` (1 = Clicked, 0 = Not Clicked)

### 🛠 Approach
- Performed **feature engineering** by extracting time-based attributes and removing irrelevant fields
- Applied **data preprocessing and encoding** for model readiness
- Implemented **Logistic Regression** using scikit-learn

### ✅ Results
- **Accuracy:** ~98%
- **Precision, Recall, F1:** ~0.98
- **Confusion Matrix:** Minimal false positives/negatives

### 🧰 Tech Stack
`Python` | `pandas` | `numpy` | `matplotlib` | `seaborn` | `scikit-learn`

---
## 2. Kyphosis Surgery Outcome Prediction
Predict whether **corrective spine surgery** was successful using **Decision Trees** and **Random Forests**.

### 📊 Dataset
- Target: `Kyphosis` (Present / Absent)
- Features: Age, Number of Vertebrae, Start Position

### ✅ Key Steps
- Implemented **Decision Tree** and **Random Forest Classifier**
- Evaluated using confusion matrix and classification metrics

### 📈 Results
- Random Forest provided higher accuracy and reduced overfitting compared to a single tree

### 🧰 Tech Stack
`Python`, `pandas`, `numpy`, `scikit-learn`, `matplotlib`
