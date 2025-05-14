# 🚢 Titanic Survival Prediction

This repository contains a complete analysis and modeling pipeline for the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/overview).  
The goal is to predict whether a passenger survived the Titanic disaster based on passenger data.

---

## 📂 Project Structure
```
├── titanic_comp.ipynb # Notebook with EDA, preprocessing, and modeling
├── final_submission.csv # Output predictions (optional)
└── README.md # Project documentation
```

---

## 🗃 Dataset

The dataset is not included in this repository due to file size limits.  
You can download it directly from the Kaggle competition page:  
🔗 [Titanic Dataset – Kaggle](https://www.kaggle.com/competitions/titanic/data)

---

## 📒 Project Overview

This is a binary classification problem where the target is `Survived` (0 or 1).  
The project includes data inspection, cleaning, feature engineering, and testing multiple classification models to predict survival.

---

## 📌 Key Insights

- `Sex` and `Pclass` were strong indicators of survival probability.
- Missing values in `Age` were imputed based on title and passenger class.
- A new feature `Title` was extracted from names, which improved prediction.
- `Cabin` was mostly missing and dropped, but a binary feature `HasCabin` was created.

---

## 🧠 Models Used

- Logistic Regression — Baseline model
- Random Forest Classifier — Performed best overall
- Support Vector Machine — Tuned with grid search
- K-Nearest Neighbors — Used for comparison

---

## 🧪 Notebook Summary

- Data exploration and missing value analysis
- Feature transformation and encoding
- Model training and evaluation (Accuracy, Confusion Matrix)
- Submission file creation for Kaggle testing

---

## ✅ Final Notes

This project showcases the full cycle of a classification task with tabular data, including data wrangling, model tuning, and insight extraction.  
Further improvements could include more feature interactions or use of ensemble stacking.
