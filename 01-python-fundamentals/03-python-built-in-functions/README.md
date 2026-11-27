# Lesson 03 — Python Built-in Functions

## Mini-Project 03: Pharmaceutical Distribution Performance Analysis

A learning exercise analysing six pharmaceutical products using core Python, without pandas or NumPy.

## Concepts applied

- Data cleaning while preserving the original list
- Truthiness checks using `all()`
- Record alignment using `zip()` and `enumerate()`
- Aggregation using `sum()`, `len()`, `min()` and `max()`
- Forecast error using `abs()`
- Inventory packaging using `divmod()`
- Non-mutating ranking using `sorted()`

## Results

| Metric | Result |
|---|---:|
| Predicted sales | 5,800 units |
| Corrected actual sales | 6,170 units |
| Average sales | 1,028.33 units |
| Aggregate absolute forecast error | 6.00% |
| Best-selling product | Vitamin C (1,650 units) |
| Least-selling product | Cetirizine (620 units) |
| Vitamin C revenue | ₦577,500.00 |
| Remaining stock | 2,180 units |
| Packaging | 90 cartons and 20 loose units |

## Analytical takeaways

Aggregate forecast errors can conceal offsetting product-level errors. Sales volume alone does not determine revenue, and truthiness is not comprehensive data validation.

## Files

- [Completed notebook](mini_project_03.ipynb)
- [Project requirements](project_requirements.txt)

Run the notebook in Jupyter with Python 3. No third-party packages are required.
