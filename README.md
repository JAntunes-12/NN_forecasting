# NN_forecasting
This was a project developed for a course of data science. 
The project was made as a challenge and the main goal was to, based on the given data set "SASUP_Sales.xlsx", use a neural network model to obtain forecasts for the sales.

# Methodology
Since the time for this challenge was very limited the data exploration phase was very simple and limited itself to dealing with N/A values.
It was used a holdout approach for data splitting.
In order to make the first implementation easier, only the sales data were considered.
Due to the time component present in this specific challenge Recurrent Neural Networks were chosen. From these, two variations were implemented: Long Short Term Memory (LSTM) and Gated Recurrent Unit (GRU).

# Challenges
The goal was to use more information than just the sales figures to obtain a prediction model. However, I was not able to make the code work

# Possible future work
Perform PCA analysis on the attributes given in order to define which should be used used for the forecasting model.
Develop the model to take into account more that just one attribute.
