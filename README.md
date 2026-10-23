# Budget Analysis and Monthly Expense Forecasting

A Python and machine-learning project exploring transaction data, spending patterns, and next-month expense forecasting.

## Project Overview

The notebook covers data inspection, cleaning, exploratory analysis, feature engineering, a Random Forest regression experiment, and visualizations of monthly expenses and income.

## Tools Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / JupyterLab

## Workflow

1. **Inspect the data:** review dataset dimensions, data types, missing values, and summary statistics.
2. **Clean the data:** normalize transaction types, payment modes, locations, and categories; convert dates and amounts; handle invalid or missing values; and remove duplicate rows.
3. **Explore spending:** inspect transaction patterns and create category, payment-mode, and monthly income-versus-expense visualizations.
4. **Prepare forecasting features:** aggregate expenses by month and create lag features, rolling statistics, and calendar features.
5. **Train and evaluate:** fit a Random Forest regressor using a chronological train/test split and evaluate its predictions with MAE, RMSE, and R².

## Dataset

The notebook expects a CSV file named `budgetwise_finance_dataset.csv` in the notebook's working directory.

The dataset is **not included** in this repository. Obtain a legitimate copy from the dataset's original source, check its licence and redistribution terms, and place it beside the notebook before running it. The source has not been verified or documented here, so this README does not attribute the data to a particular provider.

## Getting Started

Use Python 3 and create a virtual environment if desired.

Install dependencies:

```bash
pip install -r requirements.txt
```

Clone the repository and open the notebook:

```bash
git clone https://github.com/AkshatRajput16/Budget-Analysis-Forecasting.git
cd Budget-Analysis-Forecasting
jupyter notebook budget_analysis.ipynb
```

Make sure the CSV file is in the current working directory, then run the notebook cells in order. The saved notebook outputs are included, but results have not been independently reproduced in a fresh environment because the dataset is not included here.

## Saved Forecasting Result

The notebook's saved Random Forest run reports:

| Metric | Saved result |
|---|---:|
| Mean Absolute Error (MAE) | 72,424.82 |
| Root Mean Squared Error (RMSE) | 89,003.57 |
| R² | -0.3812 |

These values are the saved results from the notebook, not a newly rerun evaluation. The negative R² indicates that this model performed worse than a test-set mean-prediction benchmark on the recorded test sample. The test split contains only nine observations, so the result is limited and should not be treated as evidence of reliable forecasting performance.

## Limitations and Next Steps

- The dataset is not included, and its original source/licence needs to be documented.
- Re-run the notebook from a clean environment to confirm reproducibility.
- Compare the model with simple baselines and use chronological backtesting over multiple periods.
- Review feature timing and forecast errors before drawing conclusions.
- Add a concise findings section after verifying the analysis and results.

## Author

**Akshat Rajput**  
GitHub: [AkshatRajput16](https://github.com/AkshatRajput16)
