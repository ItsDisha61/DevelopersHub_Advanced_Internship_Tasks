# Task 3: Energy Consumption Time Series Forecasting

## Task Objective

The objective of this project is to forecast short-term household energy consumption using historical household power consumption data. Three forecasting models (ARIMA, Prophet, and XGBoost) were implemented and compared to identify the most accurate model.

---

## Your Approach

- Loaded and explored the Household Power Consumption dataset.
- Parsed and combined the Date and Time columns into a Datetime format.
- Handled missing values and converted numerical columns.
- Resampled the data into hourly intervals.
- Performed feature engineering by creating Hour, Day, Month, Weekday, and Weekend features.
- Built and evaluated three forecasting models:
  - ARIMA
  - Prophet
  - XGBoost
- Compared model performance using MAE and RMSE.
- Visualized the forecasting results using Prophet and Actual vs Forecast plots.

---

## Results and Findings

| Model | MAE | RMSE |
|--------|------:|------:|
| ARIMA | 0.7126 | 1.1193 |
| Prophet | 0.5948 | 0.7931 |
| XGBoost | 0.5204 | 0.7011 |

### Key Findings

- XGBoost achieved the lowest MAE and RMSE, making it the best-performing forecasting model.
- Prophet performed better than ARIMA.
- Time-based feature engineering improved prediction performance.
- The Actual vs Forecast visualization showed that XGBoost predictions closely followed the actual household energy consumption values.

---

## Dataset

The Household Power Consumption dataset is too large to upload to this GitHub repository. It can be downloaded from the original dataset source and placed in the project folder before running the notebook.
