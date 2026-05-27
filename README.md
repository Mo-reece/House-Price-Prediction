# House Price Prediction

Regression analysis project for predicting residential house prices using the King County housing dataset.

## Problem Statement

The goal is to estimate house sale prices from property features such as bedrooms, bathrooms, square footage, location-related variables, and condition. This is a classic regression problem that demonstrates data cleaning, exploratory analysis, feature engineering, and model evaluation.

## Why This Project Matters

Real estate pricing is a practical business problem. A clean project can show that a junior data scientist understands how to move from raw tabular data to a model, interpret model performance, and communicate limitations.

## Current Scope

- Load and inspect the housing dataset.
- Clean missing values and prepare numerical features.
- Explore relationships between house attributes and price.
- Train baseline regression models.
- Compare model performance using regression metrics.

## Tech Stack

- Python
- pandas and NumPy
- scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook

## Project Structure

```text
.
├── RealEstate.ipynb
├── requirements.txt
├── LICENSE
└── README.md
```

## Setup

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## Usage

Open `RealEstate.ipynb` and run the cells in order.

## Portfolio Status

This is currently a learning/practice project. It should not be pinned until it has:

- A cleaned dataset-loading path that works from a fresh clone.
- A results table with MAE, RMSE, and R2.
- Clear model comparison between baseline, Ridge, and polynomial features.
- A short business interpretation of the most important drivers of price.

## Future Improvements

- Move reusable preprocessing into a Python script.
- Add train/test metric reporting in a table.
- Add a short model card.
- Add plots for residuals and feature relationships.

## Author

Maurice Leonard Okurut
