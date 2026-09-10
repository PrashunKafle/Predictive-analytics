# Predictive Analytics

A project by Prashun Kafle for predicting monthly U.S. land border-crossing volumes using historical port, location, crossing category, and date information.

## What I did

- Cleaned the data, handled missing values, and explored patterns and correlations.
- Created seasonal, lag, and rolling-average features.
- Compared Linear Regression, Random Forest, and Histogram Gradient Boosting using RMSE, MAE, and R-squared.
- Explored model tuning and train/test performance gaps.
- Added actual-versus-predicted charts and a six-month forecast for selected busy port and crossing-category combinations.

## Files

- `KafleDeliverable1.ipynb`: problem statement, data dictionary, and initial cleaning.
- `KafleDeliverable2.ipynb`: exploratory analysis, correlation analysis, and PCA exploration.
- `KafleDeliverable3.ipynb`: modeling and evaluation.
- `KafleDeliverable4.ipynb`: final analysis, model comparisons, and forecasting. Start here.
- `Border_Crossing_Entry_Data.csv`: dataset used by the notebooks.
- `Predicting the Volume of Border-Crossing.pptx`: final project presentation.

## Run

Install the dependencies from the repository folder:

```bash
python -m pip install -r requirements.txt
jupyter notebook
```

Open a notebook and run its cells in order. Keep the CSV in the same folder as the notebooks. Model training and hyperparameter searches can take time.

Data source: [Border Crossing Entry Data](https://catalog.data.gov/dataset/border-crossing-entry-data-683ae).
