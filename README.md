# ML-Projects
# 🧠 Predicting Advertisement Clicks using User Behavior Data

This project aims to predict whether a user will click on an online advertisement based on their behavior and demographic data. We use **Logistic Regression**, a powerful and interpretable classification algorithm, to perform binary prediction (click or no click).

---

## 📊 Dataset

The dataset includes features like:

- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Gender (Male/Female)
- Timestamp of Ad Display
- Ad Click (Target: 1 = Clicked, 0 = Not Clicked)

---

## 🧪 Features Extracted

From the `Timestamp` column, extracted:
- `Hour` of the day
- `Month` of the year

Dropped irrelevant columns like `Ad Topic Line`, `City`, `Country`, and `Timestamp` to improve model performance.

---

## ✅ Model Used

- **Logistic Regression** (from `scikit-learn`)
- Trained on preprocessed and encoded data
- Achieved **~98% accuracy** on test data

---

## 📈 Evaluation

- **Accuracy**: 98%
- **Precision / Recall / F1**: All ~0.98 for both classes
- **Confusion Matrix**: Minimal false positives and negatives

---

## 📦 Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
