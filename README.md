# stock-prize-prediction-with-lstm
Stock prize prediction with lstm 

Discover Long Short-Term Memory (LSTM) networks in Python and how you can use them to make stock market predictions!....

# Downloading the Data

Data found on Kaggle is a collection of csv files and you don't have to do any preprocessing, so you can directly load the data into a Pandas DataFrame.

# Data Exploration

Here you will print the data you collected in to the DataFrame. You should also make sure that the data is sorted by date, because the order of the data is crucial in time series modelling.

# Data Visualization
Now let's see what sort of data you have. You want data with various patterns occurring over time.

# Splitting Data into a Training set and a Test set
You will use the mid price calculated by taking the average of the highest and lowest recorded prices on a day.

# Prediction via Averaging
Averaging mechanisms allow you to predict (often one time step ahead) by representing the future stock price as an average of the previously observed stock prices. Doing this for more than one time step can produce quite bad results. You will look at two averaging techniques below; standard averaging and exponential moving average. You will evaluate both qualitatively (visual inspection) and quantitatively (Mean Squared Error) the results produced by the two algorithms.

-->Standard Average
-->Exponential Moving Average

# lstm for prediction
-->Cell state (ct) - This represents the internal memory of the cell which stores both short term memory and long-term memories</br>
-->Hidden state (ht) - This is output state information calculated w.r.t. current input, previous hidden state and current cell input which you eventually use to predict the future stock market prices. Additionally, the hidden state can decide to only retrive the short or long-term or both types of memory stored in the cell state to make the next prediction.</br>
-->Input gate (it) - Decides how much information from current input flows to the cell state</br>
-->Forget gate (ft) - Decides how much information from the current input and the previous cell state flows into the current cell state</br>
-->Output gate (ot) - Decides how much information from the current cell state flows into the hidden state, so that if needed LSTM can only pick the long-term memories or short-term memories and long-term memories</br>

# output
Running for <strong>11000</strong> data and prediction for them.

