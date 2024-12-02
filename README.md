# Crypto Coin Price Prediction Using Long-Short-Term-Model Algorithm in Neural Networks

## Developers
- 214210050 Furkan Demircan
- 214210056 Eray Elagoz

## Objective
This project aims to leverage machine learning and deep learning techniques to develop an accurate and reliable model for predicting and forecasting Ethereum prices. By utilizing historical data and relevant features, the model provides insights into potential future trends of Ethereum, assisting investors, traders, and researchers in making informed decisions in the cryptocurrency market.

## Libraries
- numpy
- pandas
- matplotlib
- yfinance
- datetime
- sklearn
- tensorflow

## Installation
To install the required libraries, run:
```sh
pip install -r requirements.txt
```

## Usage
1. **Fetch Ethereum Data**: The data is fetched using the `yfinance` library.
2. **Data Preprocessing**: The data is scaled and prepared for the LSTM model.
3. **Model Training**: An LSTM model is trained on the preprocessed data.
4. **Prediction**: The model predicts future Ethereum prices.
5. **Evaluation**: The model's performance is evaluated using various metrics.

## Example
To run the notebook, open `index.ipynb` in Jupyter Notebook or Jupyter Lab and execute the cells step by step.

## Results
The results include plots of actual vs predicted prices, and evaluation metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE).

## License
This project is licensed under the MIT License.