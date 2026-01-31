# Consumer Demand Forecasting


## Business Problem
Forecast daily product demand across stores to optimize inventory and reduce stockouts.


## Dataset
Kaggle – Store Item Demand Forecasting Challenge


## Models Used
- Linear Regression (baseline)
- Random Forest Regressor


## Results
- MAE improved by ~20% vs baseline
- Lag and rolling mean features were strongest predictors


## How to Run
```bash
pip install -r requirements.txt
python scripts/run_pipeline.py
```
```
