# Explore SampleSuperstore

Exploratory data analysis of the SampleSuperstore dataset from Kaggle, which contains sales and profit data for a superstore. The goal is to understand the data, find patterns, and spot areas where the store can improve its profit.

## Files

- `SampleSuperstore.csv`: the dataset
- `SampleSuperstore.ipynb`: the analysis notebook

## What was done

1. Explored the data with `head()`, `info()` and `describe()`.
2. Handled missing values and removed duplicate rows.
3. Visualized the data with Matplotlib and Seaborn: sales and profit by category, sub-category and region, ship mode counts, discount vs. profit, sales vs. profit, and the distribution of profit.
4. Checked the correlation between numerical variables with a heatmap.

## Findings

- Furniture generates very low profit.
- Office Supplies generates moderate profit.
- The number of items sold does not affect profit, so profit per item is inconsistent.
- Discounts do not lead to higher profit.
- Some states have negative mean profit: Ohio, Colorado, North Carolina, Tennessee, Pennsylvania, Texas, Illinois, Arizona, Oregon, Florida.

## Recommendations

- Increase Furniture sales to raise overall profit.
- Use a recommendation system to suggest Office Supplies when customers buy Furniture or Technology products.
- Adjust prices so profit grows as the number of items increases.
- Manage discounts carefully, especially on larger orders.
- Focus on improving profit in the loss-making states listed above.
