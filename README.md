# Insurance_Predict
This is a deep learning model designed to predict the insurance premium of an individual
The neural network utilizes structured data (a CSV document) with the following features: sex, age, BMI, number of dependents, drug usage and location.

We commence by becoming one with the dataset and visualizing the relationship between features.
We make a column transformer to one-hot encode categorical features and normalize other numerical values.

A neural network is designed using the keras functional API with 2 dense layers between the input and output layers.
During compilation, the Mean Absolute Error (MAE) was programmed as the loss function and the optimizer as Nadam.
The model was trained for 100 epochs.

On the validation dataset, the MAE was calculated to be approximately 3161.
