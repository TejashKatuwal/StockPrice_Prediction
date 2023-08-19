# Importing Packages
Run the following code to download yfinance and import other necessary packages.
![Importing-1](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/576a5f60-2e19-4311-91b2-42909f7f9fe5)
![importing-2](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/1e7b8f4e-1f1c-45bc-ab2e-bd29ea927cba)

# Using yfinance to download stock prices from jan 1 2016 to 1 oct to 2021
Using the yfinance we download the stock prices, here we are downloading the stock prices from Jan 1 2016 to 1 Oct 2021.
![yfinance-1](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/8871eec6-e95f-4cb7-aee7-52263611dc6c)

# Visualising the Stock price history
Before predicting the stock prices it is necessary for machine to understand the trend oh how stock prices are varying over the years which is being displayed in the figure.
![yfinance-2](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/fa304001-1083-4633-b077-99c711675dba)

# Data Pre Processing
# Splitting the Data
We split the data into train and test sets as shown in the figure.
![split](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/8d903dc5-5a81-4930-8428-76bb7b29a4a0)

We are using 60 days windows for historical prices and following 60 days as label data as shown below.
![window](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/d76d1b98-608c-448c-ad6c-53c51a760a31)

# Preparing test data
![preparing](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/6ebb91a8-a28d-4ff5-84b1-034c9a9a458a)

# Training the LSTM
Here loss function mean squared error is used as linear regression is performed.
![train-1](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/e188d88d-d9bf-4e00-8eaa-0ec247ea8edf)

# Model Evaluation
# inverse_transform denormalizes the predicted stock prices
![pred](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/59ed0b10-8382-43d8-98c9-bcc79bfa2c5d)

# Visualizing the Predicted Prices
Here in the graph Blue graph means training set , orange means validation set and green means test set. As you can see in the figure the three graphs are perfectly aligned so the predicted prices are extremely accurate.
![output-3](https://github.com/TejashKatuwal/StockPrice_Prediction/assets/118622724/66a5ede5-1907-4e70-a403-e412c24baf42)







