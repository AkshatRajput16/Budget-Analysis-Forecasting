# Budget Analysis and Forecasting

This repository contains an exploratory analysis and monthly expense-forecasting notebook built with Python, Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.

## Project scope

- Explore and clean transaction records.
- Standardize transaction categories, payment methods, locations, dates, and amounts.
- Analyze expense patterns by month, category, and payment method.
- Engineer lag, rolling-statistic, and calendar features for a next-month expense forecasting experiment.
- Evaluate a Random Forest model using MAE, RMSE, and R² with a chronological train/test split.

## Dataset

The notebook expects `budgetwise_finance_dataset.csv` in the project root. The dataset is not included in this repository. Add it only if you have verified its source and permission to redistribute it. Update the data-loading path if you store it elsewhere.

## Run locally

1. Install Python 3.10 or later.
2. Create and activate a virtual environment.
3. Install dependencies: `pip install -r requirements.txt`
4. Place the permitted dataset file in the project root.
5. Open `budget_analysis.ipynb` in Jupyter Notebook or JupyterLab and run the cells from top to bottom.

## Evaluation note

This is an exploratory project, not a validated financial forecasting product. Forecast accuracy must be judged against simple baselines and verified by executing the complete notebook on the intended dataset. Do not interpret model predictions as financial advice.

## Limitations and next steps

- Re-run the notebook from a clean kernel to confirm reproducibility.
- Validate data quality rules and extreme transaction amounts against the dataset's documentation.
- Compare the model against mean and previous-month baselines using the same chronological test period.
- Inspect errors and document limitations before presenting metrics as results.
