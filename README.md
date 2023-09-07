# Pregnancy complication prediction using Machine Learning
This project is based on the fields of machine learning and health technology. It's about detecting pregnancy complications, status and health of fetus using several parameters like blood sugar, blood pressure, heartrate rate, etc. For this, various models are trained and tested to find the most accurate model according to a dataset, and then the dataset is compared with a real-time data to check the accuracy of the ML model.

 # The dataset source info
This file contains the information and source from which the source dataset was obtained.

 # dataset.csv
 This is the dataset used for the project
 
 # pregnancy prediction models comparison
This file contains the entire code, starting from preprocessing the data to analyzing the data, then training and testing the models based on the data set. After this, all the models are tested to predict the dataset by 10 folds to find the most accurate model.

# PCA using random forest classifier
As found out from the previous code, the PCA using the random forest lassifier model is the most accurate model, so a user interface has been developed to use the PCA using the random classifier model for further real-time data points.
