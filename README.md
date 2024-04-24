# Real Estate House Price Prediction Model
This repository contains a machine learning model for predicting the price of a new house based on various features such as the average number of rooms, tax rate, lower status, etc.
The model aims to improve the current strategy used by the real estate company, which relies on manual experts with an error rate of 25%.

### Goal: To use the model to predict house prices in a given area and invest in the area if it is undervalued.

#### Model Selection
Since we have features and labels (husing.data), supervised learning model must be used. As we need to find the house price, which is a value, we will use a regression algorithm.

#### Performance Measure
The Root Mean Square Error (RMSE) is the chosen performance measure for this particular problem.

#### Coding
The code for the ML model is written in a Jupyter notebook, making it easy to document and use the code as a notebook. 
The Jupyter Notebook is an open-source web application that allows us to create and share documents that contain live code, equations, visualizations and narrative text.

## Histogram Plot
The histogram plot showcases the distribution of data points for each feature and label in the housing dataset.
It helps in understanding the spread and concentration of values within each variable.
The x-axis represents the range of values, while the y-axis shows the frequency or count of data points falling within each range.
Observations from the histogram can provide insights into the data distribution, potential outliers, and the overall shape of the data.
Analyzing the histograms can aid in identifying patterns, trends, and potential data preprocessing requirements before building the machine learning model.

## Correaltion between different attributes
- The median value of house (MEDV) is strongly positively correlated with average number of rooms per dwelling (RM). 
- The median value of house (MEDV) has somewhat positive correlation with proportion of residential land zoned for lots over 25,000 sq.ft. (ZN) and also 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town (B).
- The median value of house (MEDV) is weakly positively correlated with weighted distances to five Boston employment centres (Dis) and Charles River dummy variable (CHAS).
- The median value of house (MEDV) is strongly negatively correlated with % lower status of the population (LSTAT).

## Pipeline
Three algorithms were chosen for building the ML model to predict house prices based on various features: linear regression, decision tree regression, and random forest regression. 
The RMSE value was least for the random forest model, which was therefore selected as the final model (Real_Estate.joblib).

The model can now be used by the real estate company for the prection of house prices. 

