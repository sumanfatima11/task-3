# Energy Consumption Time Series Forecasting

## Task 3: Development Based on Data Insights

### Objective
Forecast short-term household energy usage using historical time-based patterns.

### Dataset
[Household Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption)

### Work Performed
- Parsed and resampled time series data for consistent intervals  
- Engineered time-based features such as:
  - Hour of day
  - Weekday / Weekend  
- Trained and compared forecasting models:
  - ARIMA
  - Prophet
  - XGBoost  
- Visualized actual vs. forecasted energy usage for performance assessment  

### Skills Gained
- Time series forecasting techniques  
- Feature engineering for temporal data  
- Model comparison and evaluation using MAE and RMSE  
- Temporal data visualization using Python libraries  

### How to Run
1. Clone this repository  
2. Install required libraries:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn prophet xgboost
