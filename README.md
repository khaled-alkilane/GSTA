# GSTA for travel time prediction
A deep learning approach for predicting Travel Times.

This code is an implemnetaion of the paper titled "GSTA: Gated Spatial-Temporal Attention Approach for Travel Time Prediction".

We have provided sample of 100K trips for each of NYC and Chengdu Taxi datasets.

The sample data is already pre-processed and randomly splitted into train (X_train, Y_train), validation (X_val, Y_val), and test (X_test, Y_test).

We have implemented the prediction model for each dataset in a separate jupyter notebook (GSTA on NYC, and GSTA on Chengdu).

The dependens Libraries are:
Keras 2.4.3 
Tensorflow 2.3.0
bokeh 2.2.1
Numpy 1.19.3
Pandas 1.1.5
Sklearn.
