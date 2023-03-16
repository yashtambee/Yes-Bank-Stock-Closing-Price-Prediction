# Yes-Bank-Stock-Closing-Price-Prediction



![Screenshot 2023-03-16 152238](https://user-images.githubusercontent.com/121399834/225580652-aeaec902-18dc-4406-a742-1df92a772134.png)



### Introduction
This is a project to predict the stock price of Yes Bank using machine learning algorithms. 

The goal of the project is to develop a predictive model that can accurately forecast the future prices of Yes Bank's stock based on historical data.

### Data
Historical stock prices of Yes Bank from year 2005 to 2020 are used as the data source for this project. 
The information comprises monthly closing prices, opening prices, highest and lowest prices. The data is provided as CSV files.

### Methodology
To forecast the stock prices of Yes Bank, we used multiple machine learning methods, including Linear Regression, Lasso Regression, Ridge Regression, Elastic Net Regression, and XGBoost Regressor.

We evaluated the models based on the mean squared error (MSE), mean absolute error(MAE), mean absolute percentage error(MAPE), root mean squared error(RMSE) and R-squared (R²) metrics. We also compared the performance of the models using cross-validation.

### Results
Our research revealed that the XGBoost Regressor model performed the best, with an MSE of 0.003 and an R2 of 0.98. This model had a high degree of accuracy in predicting Yes Bank stock prices.

### Dependencies
The project requires the following dependencies to be installed:

> - python 3.0
> - pandas
> - numpy
> - sklearn
> - matplotlib
> - seaborn
> - scipy
> - XGBoost
> - statsmodels

### Usage
1. Clone the repository to your local machine.
2. Open the terminal or command prompt and navigate to the project directory.
3. Run the yes_bank_stock_price_prediction.ipynb file using Jupyter Notebook or any other IDE of your choice.
4. Or open the code in google colab , upload the data_YesBank_StockPrices csv & run all cells (press Ctrl + F9)

The file contains all the code and explanations needed to run the project.

### Conclusion
This project demonstrates the use of machine learning algorithms to predict the stock prices of Yes Bank. 

The XGBoost Regressor model was found to be the most accurate in predicting the stock closing prices. 

Based on the closing price, the model can be used to assist investors in making well-informed decisions regarding the purchase or sale of Yes Bank's stock.
