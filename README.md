# Rainfall Prediction using Machine Learning

This project aims to build a classifier that predicts whether it will rain the following day or not. The dataset used is from the Australian Government's Bureau of Meteorology and contains information about daily weather observations from numerous Australian weather stations. The project involves cleaning the data and applying various machine learning algorithms to build classifiers that can predict whether there will be rain the following day.

## Dataset

The dataset contains various features such as location, date, minimum and maximum temperatures, rainfall, humidity, wind speed, and pressure. The dataset contains over 1.5 million rows, and it is available for download from [here]('https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillUp/labs/ML-FinalAssignment/Weather_Data.csv').

## Machine Learning Algorithms

The following algorithms will be used to build the classifiers:

1. Linear Regression
2. K-Nearest Neighbors (KNN)
3. Decision Trees
4. Logistic Regression
5. Support Vector Machines (SVM)

## Evaluation Metrics

The accuracy of each classifier will be reported using the following metrics:

1. Accuracy Score: The ratio of correctly predicted observations to the total number of observations.
2. Jaccard Index: The intersection over the union of the predicted and actual labels.
3. F1-Score: The harmonic mean of precision and recall.
4. LogLoss: The logarithm of the likelihood function, used for evaluating binary classification problems.
5. Mean Absolute Error: The average of the absolute difference between predicted and actual values.
6. Mean Squared Error: The average of the squared difference between predicted and actual values.
7. R2-Score: The proportion of variance in the dependent variable that is predictable from the independent variable.

## Conclusion

This project will provide valuable insights into the application of various machine learning algorithms to build classifiers for predicting rainfall. By evaluating the performance of each algorithm using multiple metrics, we can determine which algorithm is most effective for predicting rainfall. The project will also help in understanding the importance of data preprocessing and feature selection for building accurate classifiers.
