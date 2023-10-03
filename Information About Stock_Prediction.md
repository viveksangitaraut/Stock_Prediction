# Stock_Prediction
TO PREDICT THE STOCK PRICE OF ANY COMPANY USING LSTM.

## ABOUT DATASET
This dataset contains historical data of Google's stock prices and related attributes. It consists of 14 columns and a smaller subset of 1257 rows. Each column represents a specific attribute, and each row contains the corresponding values for that attribute.

## Google Stock Prediction
This dataset contains historical data of Google's stock prices and related attributes. It consists of 14 columns and a smaller subset of 1257 rows. Each column represents a specific attribute, and each row contains the corresponding values for that attribute.

The columns in the dataset are as follows:

-  Symbol: The name of the company, which is GOOG in this case.

-  Date: The year and date of the stock data.

-  Close: The closing price of Google's stock on a particular day.

-  High: The highest value reached by Google's stock on the given day.

-  Low: The lowest value reached by Google's stock on the given day.

-  Open: The opening value of Google's stock on the given day.

-  Volume: The trading volume of Google's stock on the given day, i.e., the number of shares traded.

-  adjClose: The adjusted closing price of Google's stock, considering factors such as dividends and stock splits.

-  adjHigh: The adjusted highest value reached by Google's stock on the given day.

-  adjLow: The adjusted lowest value reached by Google's stock on the given day.

-  adjOpen: The adjusted opening value of Google's stock on the given day.

-  adjVolume: The adjusted trading volume of Google's stock on the given day, accounting for factors such as stock splits.

-  divCash: The amount of cash dividend paid out to shareholders on the given day.

-  splitFactor: The split factor, if any, applied to Google's stock on the given day. A split factor of 1 indicates no split.


# STEPS INVOLVED :

### 1. IMPORTING LIBRARIES AND DATA TO BE USED
-  You import the relevant Python libraries, such as TensorFlow, Pandas, NumPy, and Matplotlib, at this stage.
-  You also load your time series data into Python, often as a DataFrame or array.

### 2. GATHERING INSIGHTS
-  In order to fully understand your dataset's features, you must first explore it.
-  You can determine any patterns or anomalies in the data, compute summary statistics, and visualise trends.

### 3. DATA PRE-PROCESSING
-  To make data appropriate for modelling, it must be cleaned and transformed during data preprocessing.
-  Handling missing numbers, scaling or normalising data, and dealing with outliers are frequent activities.


### 4. CREATING LSTM MODEL
-  Recurrent neural networks (RNNs) of the LSTM (Long Short-Term Memory) kind are utilised for time series forecasting.
-  In this stage, you use a deep learning framework like TensorFlow or Keras to design and construct your LSTM model.
-  You specify the architecture, along with the quantity of neurons, LSTM layers, and other hyperparameters.

### 5. VISUALIZING ACTUAL VS PREDICTED DATA
-  You utilise your LSTM model to predict outcomes based on your time series data after training it.
-  To evaluate the model's efficacy, you display the projected values next to the actual data.
-  Time series charts and line plots are examples of common visualisations.
  
### 6. PREDICTING UPCOMING 15 DAYS
-  You can use your LSTM model to predict upcoming data points once it has been trained and validated.
-  The most recent data points are fed into the model, and it is then used to forecast values over the following 15 days.
-  For planning or making business decisions, these forecasts might be helpful.


# Conclusion

#### In conclusion, the goal of this project is to estimate Google's stock price using a time series forecasting method based on LSTM. 
#### Importing the relevant libraries, investigating and preparing the dataset, building an LSTM model, and comparing predicted and real data are all steps in the process. 
#### The next step is to use the model to predict Google's stock price for the subsequent 15 days. 
#### By taking these actions, we can gather important information about stock price trends that may be used to inform current and next financial planning and investing decisions.







