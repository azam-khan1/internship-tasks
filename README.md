# DevelopersHub Corporation — AI/ML Internship Tasks

This repo contains my completed tasks for the AI/ML Engineering Internship at DevelopersHub Corporation. I completed 3 out of 6 tasks before the deadline.

---

## Tasks Completed

### Task 1 — Exploring and Visualizing the Iris Dataset
Loaded and explored the Iris dataset using pandas. Created scatter plots, histograms, and box plots to understand feature distributions and relationships.

- **Dataset:** Iris Dataset (150 rows)
- **Libraries:** pandas, matplotlib, seaborn
- **Folder:** `task1-iris-visualization/`

---

### Task 2 — Heart Disease Prediction
Built a Logistic Regression model to predict whether a person has heart disease based on health data. Handled missing values, encoded categorical columns, and evaluated using accuracy, confusion matrix, and ROC curve.

- **Dataset:** Heart Disease UCI Dataset (920 rows)
- **Model:** Logistic Regression
- **Accuracy:** 80.43% — ROC-AUC: 0.90
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Folder:** `task3-heart-disease/`

---

### Task 3 — House Price Prediction
Trained two regression models to predict house prices based on area features. Compared Linear Regression and Gradient Boosting and found that the simpler model performed better on this dataset.

- **Dataset:** Housing Dataset (5000 rows)
- **Models:** Linear Regression, Gradient Boosting
- **Best MAE:** $80,879 (Linear Regression)
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Folder:** `task6-house-price/`

---

## Repo Structure

```
internship-tasks/
│
├── task1-iris-visualization/
│   ├── iris-data-visualizing.ipynb
│   ├── Iris.csv
│   └── README.md
│
├── task2-heart-disease/
│   ├── task2_heart_disease.ipynb
│   ├── heart_disease_uci.csv
│   └── README.md
│
├── task3-house-price/
│   ├── task3_house_price.ipynb
│   ├── housing.csv
│   └── README.md
│
└── README.md
```

---

## Tools and Libraries

```
pandas, numpy, matplotlib, seaborn, scikit-learn
```

---

## Notes

- All models are built using scikit-learn
- Each task folder has its own README with details on the dataset, approach, and results
- Hardware used: ThinkPad, 8GB RAM, no GPU
