# Exploring Zomato Restaurant Data with Python

This project is a hands-on notebook for exploring restaurant listings and
customer behavior using the Zomato dataset.

## Learning goals

- Load a CSV dataset with pandas.
- Inspect columns, data types, and missing values.
- Explore restaurant categories, cuisines, and price levels.
- Visualize ratings, votes, and ordering patterns.
- Summarize restaurant performance by location and category.
- Practice cleaning and interpreting a real-world dataset.

## Getting started

Install the dependencies:

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

Then launch Jupyter, open `zom_analysis.ipynb`, and run the notebook cells in
order. The notebook expects `Zomato-data-.csv` in the same folder.

## Files

- `zom_analysis.ipynb` — exploratory data analysis and visualizations
- `Zomato-data-.csv` — restaurant dataset
- `order_heatmap.png` — heatmap of restaurant ordering patterns
- `votes_for_restaurants.png` — vote distribution visualization

## Before interpreting the scores

Clean the data and review missing values before drawing conclusions from
restaurant ratings or vote counts. A quick check of outliers and nulls helps
ensure the analysis reflects the dataset rather than a few noisy entries.

## Ideas to extend the project

- Compare restaurant performance by city or locality.
- Add a preprocessing pipeline for missing values and category fields.
- Report average ratings, vote counts, and price ranges by cuisine.
- Explore how restaurant features relate to customer popularity.
- Record the dataset source, license, and any assumptions.
