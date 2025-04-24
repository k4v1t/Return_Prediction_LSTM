This research project focusses on comparing simple RNN, LSTM and GRU for stock market return prediction. Using data for AAPL and HPQ from an online Kaggle datasource (https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs/code), I generated numerous EWM features from the open, high, low, close and volume data.

Using these features, I then created multiple versions of training data for the neural networks, each with different lookback and prediction horizons. I did this to not just understand how each of the neural networks perform, but also how they perform over different horizons. These input data are generated in the Feature_Generation notebooks.

Finally, using these different input data, I compared a simple RNN, LSTM and GRU in their ability to predict the return and probability of positive return over the prediction horizon. 

This entailed using a different neural network architecture depending on the use case (return or probability). All of the code for this can be found in the Return_ or Prob_ notebooks (labelled accordingly).

The research outputs and conclusions can be found in the PDF provided in this folder.
