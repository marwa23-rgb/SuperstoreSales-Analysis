<h1 align="center">🛒 Explore SampleSuperstore</h1>

<p align="center">
  Exploratory data analysis of a superstore's sales and profit data using Python
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Seaborn-Visualization-4C8CBF" alt="Seaborn">
  <a href="https://www.kaggle.com/"><img src="https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle&logoColor=white" alt="Kaggle"></a>
</p>

## 📌 Overview

This project explores the **SampleSuperstore** dataset from Kaggle. It cleans the data, visualizes sales and profit with Matplotlib and Seaborn, checks correlations between variables, and turns the findings into practical recommendations for the store.

---

## ⚡ At a Glance

| 📊 Visualizations | ⚠️ Problems Found | 💡 Recommendations | 📍 Loss-Making States |
|:---:|:---:|:---:|:---:|
| **8** | **5** | **5** | **10** |

---

## 🔄 Workflow

1. **Load & Inspect** – Reviewed the structure and contents of the data (`head()`, `info()`, `describe()`).
2. **Clean** – Checked for missing values, handled them, and removed duplicate rows.
3. **Visualize** – Built count plots, bar charts, a joint plot, a scatter plot and a histogram with Matplotlib and Seaborn.
4. **Correlate** – Computed the correlation matrix and plotted it as a heatmap.
5. **Summarize** – Turned the findings into recommendations for the store.

> **Files**  
> `SampleSuperstore.csv` · `SampleSuperstore.ipynb` · `README.md`

---

## 📊 Visualizations

| Plot | Shows |
|---|---|
| Count plot | Sales count by sub-category |
| Bar chart | Profit by sub-category |
| Count plot | Sales count by category |
| Bar chart | Sales by region |
| Joint plot | Discount vs. profit |
| Count plot | Ship mode usage |
| Scatter plot | Sales vs. profit |
| Histogram | Distribution of profit |

---

## 🔍 Key Findings

| # | Finding |
|:---:|---|
| 1 | Total profit from **Furniture** is very low |
| 2 | Total profit from **Office Supplies** is moderate |
| 3 | The number of items sold does not affect profit, so profit per item is inconsistent |
| 4 | Discounts do not lead to higher profit |
| 5 | Some states have **negative mean profit** |

**Loss-making states:** Ohio, Colorado, North Carolina, Tennessee, Pennsylvania, Texas, Illinois, Arizona, Oregon, Florida.

---

## 💡 Recommendations

- **Furniture:** increase sales to raise overall profit.
- **Office Supplies:** use a recommendation system to suggest them when customers buy Furniture or Technology products.
- **Pricing:** adjust prices so profit grows as the number of items increases.
- **Discounts:** manage them carefully, especially on larger orders.
- **States:** focus on improving profit in the loss-making states listed above.

---

## 🚀 Run It

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook SampleSuperstore.ipynb
```

## 👩‍💻 Author

**Marwa Samy** · [GitHub](https://github.com/marwa23-rgb)
