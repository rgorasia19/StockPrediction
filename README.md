# StockPrediction
A  Python project that uses machine learning (esp. LSTM/GRU models) to predict stock movements. It shows data fetching, feature engineering, model training, evaluation, and forecasting in a tidy, modular design. Built as a Jupyter Notebook to showcase how to go from nothing to a full stock prediction program. This code is still under development, I just wanted to push it to git.

## Requirements
Python 3.8+

pandas, numpy, scikit-learn, ta

TensorFlow/Keras or PyTorch

yfinance or alpha_vantage (or your preferred data source)

Optional: matplotlib/seaborn for plotting
          statsmodels
## Models
* LSTM – great for capturing temporal dependencies
* Random Forest Regressor - good at handling noisy data
* SVR Regressor
* Linear Regressor
* XGBoost Regressor
* KNeighbors Regressor
* MLP Regressor

All models are taken into a passthrough meta-learner
## License
Apache License 2.0 — do whatever you want, just don’t sue me.

