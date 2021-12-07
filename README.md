# Movie-Revenue-Prediction
Using ANN


Steps Involved ---->

1>   Import ‘Movie_collection’ csv files in data_x and data_y variables.
2>   Look at the shape and first five rows of both dataframes to understand the data.
3>   Split the data into test, train, and validation.
4>   Take a look at the shape of the test, train, and validation set.
5>   Standardize the data.
6>   Create an ANN model with 2 dense layers of 30 neurons each.
7>   Compile the model with loss="mean_squared_error", optimizer=keras.optimizers.SGD(lr=1e-2) and metrics=['mae']).
8>   Train the model for 100 epochs.
9>   Evaluate the model performance on the test set.
10>  Predict the values of the first 5 test records.
