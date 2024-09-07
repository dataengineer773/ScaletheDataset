we use scale the dataset, we will use the MinMaxScaler to scale each input variable to the range0-1 . The best practice use of this scaler is to fit it on the training datatset and then apply tramsform dataset
to the training dataset and other datatset,and in the next step we did fit a model on th etraining dataset and save both the model and the scaler objcet to file. we use  a LogisticRegression becuase the problem
is a simple binary classification and in the final step load model and the scaler object and make use of them.
