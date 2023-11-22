# Distributed-Linear-Regression-Analysis
The housing dataset is used to develop a pipeline for running a simple linear regression in a pseudo-distributed manner (single node setup) using Spark ML.
The following was implemented:
• Created a Spark session, loaded the data, parse and display them using the apache spark
ecosystem (pyspark)
• Created a feature vector separating the features from the labels, i.e. the column you
need to predict.
• Split the dataset into 70% train and 30% test set
• Train a linear regression model
• Evaluated its performance on the train and test sets, reported the mean absolute error
(MAE), the root mean squared error (RMSE) and mean squared error (MSE)
• The test set is used to generate a table showing the predicted vs actual values as well
as a predicted vs actual plot
