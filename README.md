# NEXUS
This is the official repository for NEXUS
### Overview
#### NEXUS
NEXUS - House Price Prediction Model
NEXUS is a machine learning model designed to predict the prices of houses based on the number of features passed into it. It is built using Python and several popular machine learning libraries, including Scikit-learn, NumPy, Pandas, Matplotlib and Seaborn.
### Dataset
NEXUS uses a dataset of housing prices that includes a variety of features related to each house. The dataset is stored in a comma-separated values (CSV) file, and the features included in the dataset are unique identifies for the house like price, area, bedrooms, bathrooms, stories, main road, guest-room, basement, hot water-heating, air-conditioning, parking, pref-area, furnishing status, etc.
### Preporcessing
Before building the machine learning model, the dataset undergoes a series of preprocessing steps to clean and prepare the data for analysis. The preprocessing steps include:
- Removing duplicate data: Any duplicate data points in the dataset are removed to avoid bias in the analysis.
- Removing missing data: Any missing data points are either removed or imputed using a suitable method to avoid bias in the analysis.
- Scaling the features: The features are scaled to a range between 0 and 1 using MinMaxScaler from Scikit-learn, to ensure that all features are given equal weight in the analysis.
### Model Architecture
NEXUS is built using a supervised learning algorithm known as Linear Regression. Linear Regression is a statistical method for predicting a continuous outcome variable (in this case, the price of the house) based on one or more predictor variables (the features passed into the model).
### Training and Evaluation
The model is trained on a subset of the dataset using a training set and is evaluated using a separate test set. The training set is used to fit the model parameters, and the test set is used to evaluate the performance of the model on unseen data.
The performance of the model is evaluated using a metric known as Root Mean Squared Error (RMSE). The RMSE measures the difference between the predicted values and the actual values in the test set.
### Usage
To use NEXUS to predict the price of a house, follow these steps:
1. Load the dataset into Python using a suitable method.
2. Preprocess the dataset using the preprocessing step


### Date Created
April 2023

### Creator
Gideon Ogunbanjo


<sub>Incomplete Model!!</sub>