# Airbnb Data Analysis - Rome

## Overview

This project involves analyzing a dataset of Airbnb listings in Rome to understand pricing trends, room types, and the correlation between neighborhood, room features, and pricing. It uses SQL for data exploration, machine learning (Random Forest) for predicting missing values, and visualization techniques to uncover key insights.

## Key Insights

- **Price variation by neighborhood**: Some neighborhoods, like "Castel Di Leva", are much more expensive compared to others.
- **Room types**: Entire apartments tend to be more expensive than private rooms.
- **Room features**: Number of bedrooms correlates with price, but review scores don't strongly influence pricing.
- **Machine learning**: A Random Forest model was used to predict missing neighborhood data, achieving 97% accuracy.

## Technologies Used

- **Python**: Pandas, NumPy, Scikit-learn, Seaborn
- **SQL**: Data aggregation and exploration
- **Jupyter Notebook**: For analysis and visualization

## Dataset

The dataset used is publicly available on [Airbnb Listings](https://insideairbnb.com/get-the-data/). It was cleaned and preprocessed to focus on features like price, room type, and neighborhood.

## Files Included

- **airbnb_analysis.ipynb**: The Jupyter Notebook for analysis, including code for data exploration, prediction, and visualizations.

---

### How to Run

1. Clone the repository.
2. Open the Jupyter notebook to view the analysis and outputs.
3. No extra installations required for the notebook since it uses common libraries like Pandas, Matplotlib, and Scikit-learn.
