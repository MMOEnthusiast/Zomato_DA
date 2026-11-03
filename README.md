# Exploring Zomato Restaurant Data with Python

This project is a hands-on notebook for practicing exploratory data analysis
with restaurant listings from Zomato.

## Learning goals

- Load a CSV dataset with pandas.
- Inspect columns, data types, and missing values.
- Clean and explore restaurant ratings.
- Visualize restaurant categories, customer votes, and online ordering patterns.
- Think critically about what restaurant data can—and cannot—show.

## Getting started

Install the dependencies:

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

Then launch Jupyter, open `zom_analysis.ipynb`, and run the notebook cells in
order. The notebook expects `Zomato-data-.csv` in the same folder.

## Files

- `zom_analysis.ipynb` — guided analysis and visualizations
- `Zomato-data-.csv` — restaurant dataset
- `order_heatmap.png` — visualization of ordering patterns
- `votes_for_restaurants.png` — visualization of restaurant votes

## Before interpreting the results

Restaurant ratings and vote counts are only useful when interpreted in the
context of the data. Review the notebook's cleaning steps and consider missing
values, outliers, and differences in the number of votes before drawing
conclusions.

## Ideas to extend the project

- Compare restaurant ratings and votes across categories.
- Explore how online ordering relates to restaurant ratings or popularity.
- Add a preprocessing pipeline for missing values and categorical data.
- Document the dataset source, license, and any assumptions.
