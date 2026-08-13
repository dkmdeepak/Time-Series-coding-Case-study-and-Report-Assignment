# Appliance Energy Forecasting

This project predicts hourly home appliance energy use. It uses the UCI Appliances Energy Prediction dataset.

## What it does

It builds and compares different models:
- Simple forecasts (mean, naive, seasonal naive, drift)
- SARIMAX
- XGBoost with extra features
- A foundation-model-style comparison

Each model predicts energy use 24 hours ahead. We compare their accuracy.

## Files

```
├── energy_forecasting_analysis.ipynb
├── Report.docx                        
├── LICENSE                              
├── requirements.txt                           
└── README.md
```

## How to run

1. Install packages:
```
pip install pandas numpy matplotlib statsmodels xgboost scikit-learn
```
2. Open `energy_forecasting_analysis.ipynb`.
3. Run all cells. The data will download on its own.

## Data source

[UCI Appliances Energy Prediction Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/00374/energydata_complete.csv)
