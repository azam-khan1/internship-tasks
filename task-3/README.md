# Task 6: House Price Prediction

This is part of my AI/ML internship tasks at DevelopersHub Corporation. The goal was to predict house prices based on area features like income, number of rooms, and population.

---

## Dataset

**Housing Dataset** — 5000 rows, 7 columns  
Source: Kaggle

Key columns: Avg. Area Income, Avg. Area House Age, Avg. Area Number of Rooms, Avg. Area Number of Bedrooms, Area Population  
Target column: `Price`

No missing values — dataset was clean and ready to use.

---

## What I did

- Loaded and explored the dataset using pandas
- Visualized price distribution, feature correlations, and relationships between income/rooms and price
- Dropped the `Address` column since it's just text and not useful for prediction
- Scaled features using StandardScaler for Linear Regression
- Trained two models and compared their performance

---

## Models Used

- Linear Regression (sklearn)
- Gradient Boosting Regressor (sklearn)

---

## Results

| Model | MAE | RMSE |
|-------|-----|------|
| Linear Regression | $80,879 | $100,444 |
| Gradient Boosting | $87,417 | $109,468 |

Linear Regression actually performed better here because the dataset has a strong linear relationship between features and price.

---

## Libraries

```
pandas, numpy, matplotlib, seaborn, scikit-learn
```

---

## How to run

1. Clone the repo
2. Place `housing.csv` in the same folder
3. Open `task6_house_price.ipynb` in Jupyter Notebook
4. Run all cells top to bottom