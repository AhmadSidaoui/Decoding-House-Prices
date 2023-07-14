# Decoding-House-Prices
Unveiling the Secrets Behind Property Valuations

## Dependencies

Make sure to install the following dependencies before running the code:

- pandas
- numpy
- matplotlib
- random
- os
- termcolor
- sklearn
- tensorflow
- Descriptive Analysis

The initial part of the code performs descriptive analysis on the housing dataset. It provides information on null values, data points, and data types of the variables.

## Analyzing the Price

This section of the code analyzes the relationship between housing prices and different variables such as bedrooms, bathrooms, stories, main road, guest room, basement, hot water heating, air conditioning, parking, prefarea, and furnishing status. The analysis includes bar plots to visualize the average price based on each variable.

## Linear Regression (+ Diagnosis)

The code implements linear regression modeling to predict housing prices. It prepares the data by splitting it into training, cross-validation, and test sets. Then it fits polynomial regression models of increasing degrees to the training data, scales the features, and evaluates the models using mean squared error. Finally, it selects the best model based on cross-validation error and computes the generalized error on the test set.

The code also includes visualizations of the predicted housing prices for different degrees of polynomial regression models and plots the training and cross-validation mean squared errors for each degree.
