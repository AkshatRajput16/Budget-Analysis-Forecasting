# Budget Analysis and Monthly Expense Forecasting

## Overview

This project explores personal finance transaction data to understand spending patterns and experiment with monthly expense forecasting using Python and machine learning.

The project combines exploratory data analysis (EDA), data preprocessing, feature engineering, and model evaluation to investigate whether historical spending patterns can help predict future expenses.

## Objectives

- Analyze monthly income and expense patterns.
- Identify spending trends across categories and payment methods.
- Clean and preprocess transaction data.
- Engineer time-series features for monthly expense forecasting.
- Compare machine learning models against simple forecasting baselines.

## Technologies Used

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Jupyter Notebook

## Project Workflow

1. **Data Cleaning:** Processed transaction dates, converted amount fields to numeric values, and prepared the data for analysis.
2. **Exploratory Data Analysis:** Investigated spending trends and monthly patterns using statistical summaries and visualizations.
3. **Feature Engineering:** Created lag features, rolling means, rolling standard deviations, calendar features, and cyclical month encodings.
4. **Model Development:** Experimented with Random Forest, Extra Trees, and Gradient Boosting models.
5. **Model Evaluation:** Compared predictions using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared, alongside simple forecasting baselines.

## Getting Started

### Prerequisites

Install Python and Jupyter Notebook or JupyterLab.

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the Project

1. Clone or download this repository.
2. Place the required dataset in the location expected by the notebook.
3. Open `budget_analysis.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells sequentially.

## Dataset

The notebook expects a CSV file named `budgetwise_finance_dataset.csv`.

The dataset is not included in this repository. Make sure you have a legitimate copy of the dataset before running the notebook, and verify its source and redistribution permissions before publishing it.

## Limitations

This project is an exploratory forecasting experiment, not a production-ready financial forecasting system. Model performance must be evaluated against appropriate baselines, and the notebook should be rerun from a clean environment to verify reproducibility.

## Future Improvements

- Improve data validation and outlier handling.
- Compare models using chronological backtesting.
- Investigate forecasting errors and feature importance.
- Develop a simple interactive interface for exploring spending patterns.
- Improve reproducibility and document verified model results.

## Author

**Akshat Rajput**

GitHub: [AkshatRajput16](https://github.com/AkshatRajput16)
