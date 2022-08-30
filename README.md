# Predicting_Hand_Written_Data
Logistic Regression Model

How scikit-learn can be used to recognize images of hand-written digits, from 0-9

The digits dataset consists of 8x8 pixel images of digits. The images attribute of the dataset stores 8x8 arrays of grayscale values for each image. The target attribute of the dataset stores the digit each image represents.

We can then split the data into train and test subsets and fit a support vector classifier on the train samples. The fitted classifier can subsequently be used to predict the value of the digit for the samples in the test subset.
