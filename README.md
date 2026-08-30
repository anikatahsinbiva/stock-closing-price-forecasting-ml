# stock-closing-price-forecasting-ml
# S&P 500 Closing Price Forecasting

This repository contains Python code for forecasting the **S&P 500 closing price** using various machine learning and deep learning models.

The S&P 500 historical data was collected from **Yahoo Finance using the `yfinance` library**. The data collection process is described separately in my repository:

**[stock-market-data-crawling](https://github.com/anikatahsinbiva/stock-market-data-crawling)**

## Dataset

* **Training period:** January 1, 2005 – December 31, 2022
* **Testing period:** January 1, 2023 – January 31, 2024

## Models

The following models are implemented:

* Artificial Neural Network (ANN)
* Gradient Boosting Machine (GBM)
* Random Forest (RF)
* Bayesian Neural Network (BNN)
* Recurrent Neural Network (RNN)
* Long Short-Term Memory (LSTM)
* Deep Neural Network (DNN)

## Evaluation Metrics

Model performance is evaluated using:

* RMSE
* MAE
* MAPE
* MSLE
* R²
* MFE
* MPE

## File

* **`forecasting_SP500_closing_price_ml.ipynb`** — Contains the complete Python code for data preprocessing, model implementation, forecasting, and model evaluation.


## Requirements

The project is implemented in Python and can be run using **Google Colab** or **Jupyter Notebook**.

Main libraries include:

```text
Python
NumPy
Pandas
Matplotlib
Scikit-learn
TensorFlow
```

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload ` sp500_historical_prices.csv`.
3. Install the required libraries if necessary.
4. Run the notebook cells sequentially.
