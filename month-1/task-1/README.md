# Task 1: Exploring and Visualizing the Iris Dataset

This is part of my AI/ML internship tasks at DevelopersHub Corporation. The goal was to load, explore, and visualize the Iris dataset to understand data trends and distributions.

---

## Dataset

**Iris Dataset** — 150 rows, 6 columns  
Source: Kaggle / seaborn built-in

Columns: SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm, Species

---

## What I did

- Loaded the dataset using pandas
- Checked shape, column names, and first few rows using `.head()`
- Used `.info()` and `.describe()` for summary statistics
- Created a scatter plot to show the relationship between sepal length and width
- Plotted histograms to show value distributions for sepal features
- Used a box plot to identify outliers across all features

---

## Libraries

```
pandas, matplotlib, seaborn
```

---

## How to run

1. Clone the repo
2. Place `Iris.csv` in the same folder
3. Open `iris-data-visualizing.ipynb` in Jupyter Notebook
4. Run all cells top to bottom