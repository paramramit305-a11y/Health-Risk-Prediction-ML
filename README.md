# Health Risk Prediction using Machine Learning

A machine learning project for **NovaGen Research Labs** to classify individuals as **healthy** or **at health risk** based on clinical and lifestyle data.

---

## Problem Statement

NovaGen Research Labs conducts large-scale population health studies but lacks a reliable way to distinguish healthy individuals from those at higher health risk. The goal is to build a predictive model using health records from **9,800 individuals** to support participant selection for clinical trials and risk-based population analysis.

---

## Dataset

9,549 records with 23 features including physiological measurements (Age, BMI, Blood Pressure, Cholesterol, Glucose Level), lifestyle factors (Smoking, Alcohol, Diet, Exercise, Sleep), and encoded categorical variables (Blood Group, Diet Type).

**Target:** `0` = Healthy | `1` = Unhealthy

---

## Models & Results

Since missing an at-risk individual has serious consequences, **Recall** is the primary evaluation metric.

| Model | Recall | Precision | F1 Score | Accuracy |
|---|---|---|---|---|
| Logistic Regression | 0.8376 | 0.8286 | 0.8331 | 0.8225 |
| KNN | 0.8832 | 0.8902 | 0.8867 | 0.8806 |
| SVM | 0.9426 | 0.9324 | 0.9375 | 0.9335 |
| Decision Tree | 0.8891 | 0.9062 | 0.8976 | 0.8927 |
| Random Forest | 0.9396 | 0.9471 | 0.9433 | 0.9403 |
| Naive Bayes | 0.8099 | 0.8450 | 0.8271 | 0.8209 |
| Gradient Boosting | 0.9248 | 0.9211 | 0.9229 | 0.9183 |
| **XGBoost** ⭐ | **0.9416** | **0.9548** | **0.9482** | **0.9455** |

**Best Model: XGBoost** — 94.55% accuracy, 94.43% cross-validation score (5-fold)

---

## How to Run

```bash
git clone https://github.com/paramramit305-a11y/Health_Risk_Prediction.git
pip install pandas scikit-learn xgboost matplotlib seaborn
jupyter notebook Health_Risk_Prediction_using_Machine_Learning.ipynb
```

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 🚀 My AI/ML Journey

I'm **Amit Parmar**, an AIML student on the path to becoming an **AI Engineer**.

This is part of my ongoing project series:

| Phase | Focus | Status |
|---|---|---|
| 📌 Current | Machine Learning Projects | 🔄 In Progress |
| 🔜 Next | Deep Learning Projects | ⏳ Upcoming |
| 🎯 Goal | AI Engineer | 🚀 Building towards it |

> *"Every model trained is one step closer to the goal."*

---

## Author

**Amit Parmar**
GitHub: [@paramramit305-a11y](https://github.com/paramramit305-a11y)

---

*Developed as part of the NovaGen Labs Data Science challenge.*
