# StockPricePrediction
This ML model was built to predict stock prices. Multiple EDA and preprocessing techniques were used to prepare the dataset to train the model. Multiple models were evaluated using directional accuracy and RMSE, such as RandomForest, Gradient Boosting, Liner Regression, SVR and LSTM, to determine which model to use.

Findings: 

| Model                                  | Directional Accuracy (%)| RMSE                 |
|----------------------------------------|-------------------------|----------------------|
| Linear Regression                      | 50.05                   | 0.0868               |
| Random Forest                          | 49.52                   | 0.5509               |
| Ridge Regression                       | 48.75                   | 0.0923               |
| XGBoost                                | 48.03                   | 0.5541               |
| SVR                                    | 50.14                   | 0.7367               |
| Gradient Boosting                      | 49.86                   | 0.5581               |
| LSTM                                   | **68.92**                   | **0.0525**               |
| LSTM + Soft Voting (LSTM, SVR, GB)     | 68.78                   | 0.1654               |

To reproduce these results, refer to the Jupiter notebook and "question4-stock-data.csv" file in this repository. 

You can also clone this repository using:<br>
```git clone https://github.com/naheem88/StockPricePrediction.git```<br>

Run using this:<br>
```cd StockPricePrediction```

