#  SECOND HAND CARS DATA SET
## Regression problem - using `TensorFlow `

### <u>Description:</u>
###  This code is a script for building and training a machine-learning model for predicting the price of second-hand cars.
### This code uses libraries such as TensorFlow, pandas, seaborn, and matplotlib for data processing, visualization, and model building.
### Data preparation is performed by reading a CSV file `("train.csv")` containing car features and labels, and then exploring the data using visualizations.
### The data is normalized using the Normalization layer from TensorFlow. <br> The model architecture is defined using the Sequential API from Keras, consisting of several dense layers with relu activation and a final output layer. <br> The model is compiled with an optimizer (Adam), loss function (MeanAbsoluteError), and metrics (RootMeanSquaredError). <br><br> The model is trained using the training dataset and validated using the validation dataset. Training history and performance metrics are plotted. <br> <br>Finally, the trained model is evaluated on the test dataset, and predictions are made on new car data.
