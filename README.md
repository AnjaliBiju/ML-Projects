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

## 3. Loan Repayment Prediction

This project predicts whether a borrower will fully repay their loan using historical **LendingClub** data (2007–2010). The goal is to assist investors in assessing credit risk before lending.

### 📊 Dataset
- **Source:** LendingClub.com (2007–2010)
- **Target:** `not.fully.paid` (1 = Defaulted, 0 = Fully Paid)
- **Features:** Credit policy, FICO score, interest rate, purpose, and other borrower details.

### 🛠 Approach
- Performed **data preprocessing** and handled categorical variables using one-hot encoding.
- Implemented:
  * **Decision Tree Classifier**
  * **Random Forest Classifier**
- Evaluated with confusion matrix and classification metrics.

### ✅ Results & Insights
* **Decision Tree:** Accuracy ~73%, better on majority class, low recall for defaults.
* **Random Forest:** Accuracy ~85%, strong on fully paid loans, but weak on minority class (defaults).
* **Key Challenge:** Class imbalance → models favor majority class.
* Suggested improvements: **SMOTE, class weights, advanced ensembles**.

### 🧰 Tech Stack
`Python` | `pandas` | `numpy` | `matplotlib` | `seaborn` | `scikit-learn`


