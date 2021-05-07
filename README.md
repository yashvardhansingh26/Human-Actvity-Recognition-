# Human-Actvity-Recognition-

Here we are using Tensorflow to predict the activity that a given human is performing.
Dataset-->The dataset for the same has been taken from Kaggle which has recording of 30 participants performing their daily activity.
The dataset consist of 2 files namely- train.csv and test.csv
Getting started--> 1. Firstly, we import required libraries like numpy for mathematical calculations,matplotlib to plot the data in tables and charts,
sklearn for preprocessing of the data,and most importantly tensorflow for the prediction.
2. Then we read the data in variables from the given path
3. Then we perform data splitting in x_train,y_train and x_test,y_test
4.The various labels in our dataset- Laying, standing,sitting,walking,walkinh_upstairs,walking_downstairs
5.Then we preprocess the data using sklearn library modules- labelEncoder and MinMaxScaler
6. Then comes the training part which is done using keras with 25 epochs and save in a .h5 file
7. Then we can plot the various variables like training loss, validation loss during epochs using matplotlib library.
8.Finally evaluate the model for the accuracy.
