# Rossmann-Stores-SARIMAX
Exploring the use of SARIMAX on the Rossmann Stores Dataset from:
https://www.kaggle.com/competitions/rossmann-store-sales

For academic-style discussion please read rossmann_stores_discussion.ipynb.

rossmann.db contains dataset, csv's contain metrics and forecasts from a simple naive benchmark, SARIMAX, and XGBoost.

rossmann_stores_sarimax.ipynb trains one model for each store in the dataset, resulting in a runtime of approximately 1 hour and thirty minutes when parallelized on a Macbook M4 Pro. Please beware.

rossmann_stores_xgboost.ipynb follows the same one-to-one methodology, and trains in under 10 minutes.