# Brazil Forest Fires Analysis (2020-2024)

## About the Project
This repository contains a Data Science and Time Series study focused on forest fire outbreaks in Brazil between 2020 and 2024. 

The project goes beyond descriptive analysis by implementing predictive modeling. It compares two distinct approaches for forecasting fire outbreaks:

- ARIMA: A statistical model for capturing linear trends and seasonality.
- XGBoost: A powerful gradient-boosting machine learning algorithm for capturing non-linear patterns.

To ensure the reliability of the forecasts, both models are evaluated using a Backtesting strategy (Time Series Cross-Validation), simulating how the models would have performed on historical data.

---

## Repository Structure
The project is divided into two main stages:

1. **portfolio_fires_brazil.py:** The primary script responsible for data loading, cleaning, initial preprocessing, model adjustment and forecasting.
2. **results_analysis.py:** This script focuses on generating visualizations, calculating statistics, and performing analysis on the forecasted data.

---

## How to Run
###To replicate this analysis, follow the steps below:
Create a folder named 'fires' in the root directory, download and paste the data (csv format) in it.

### Run the processing script first to prepare the dataset:
python portfolio_fires_brazil.py

### Results Visualization:
python results_analysis.py

---

## Data Source

The data was extracted from the BDQueimadas database by INPE (National Institute for Space Research, Brazil).
- Link: https://dataserver-coids.inpe.br/queimadas/queimadas/focos/csv/anual/Brasil_sat_ref/
