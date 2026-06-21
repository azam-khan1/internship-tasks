# Task 3: Heart Disease Prediction

This is part of my AI/ML internship tasks at DevelopersHub Corporation. The goal was to build a model that predicts whether a person has heart disease or not based on their health data.

---

## Dataset

**Heart Disease UCI Dataset** — 920 rows, 16 columns  
Source: Kaggle ([link](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-uci))

Key columns used: age, sex, chest pain type (cp), cholesterol, max heart rate (thalch), and a few more.  
Target column: `num` — converted to binary (0 = no disease, 1 = has disease)

---

## What I did

- Loaded and explored the dataset using pandas
- Handled missing values by filling with column mean
- Converted categorical columns (like sex, cp, thal) using one-hot encoding
- Visualized disease distribution, age vs heart rate, and feature correlations
- Trained a Logistic Regression model
- Evaluated using accuracy, confusion matrix, and ROC curve

---

## Models Used

- Logistic Regression (sklearn)

---

## Results

| Metric | Score |
|--------|-------|
| Accuracy | 80.43% |
| ROC-AUC | 0.90 |

AUC of 0.90 means the model is pretty good at separating diseased vs healthy patients.

---

## Libraries

```
pandas, numpy, matplotlib, seaborn, scikit-learn
```

---

## How to run

1. Clone the repo
2. Place `heart_disease_uci.csv` in the same folder
3. Open `heart_disease-prediction.ipynb` in Jupyter Notebook
4. Run all cells top to bottom