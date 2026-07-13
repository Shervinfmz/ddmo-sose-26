\# DDMO SoSe 2026 - Electricity Load Forecasting



This repository contains our work for the DDMO SoSe 2026 electricity load forecasting challenge.



The goal is to forecast German electricity load for the next 24 hours using historical load data, calendar features, weather features, and machine learning models.



\## Project Structure



```text

notebooks/        Main experimental notebooks

src/              Reusable Python helper code

data/             Data documentation only; raw data is not committed

submissions/      Forecast CSV files for leaderboard submission

docs/             Methodology notes and project documentation

Current Model

The current main model uses:

historical German electricity load
calendar features
weather features
LightGBM regression
recent clean 7-day backtesting
comparison against weekly persistence
Backtesting

The main evaluation metrics are:

MAE
RMSE
MAPE
comparison against weekly persistence

## Security

This repository uses GitHub CodeQL and OpenSSF Scorecard for automated security analysis.

For vulnerability reporting information, see [SECURITY.md](SECURITY.md).
Notes


Large raw data files, cached files, and trained model files are not committed to this repository.

