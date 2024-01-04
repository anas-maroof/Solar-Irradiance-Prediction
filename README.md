# Solar-Irradiance-Prediction

# Overview
This project focuses on predicting solar irradiance, a measure of the sun's energy reaching Earth, using meteorological data from the HI-SEAS weather station. The dataset spans four months (September to December 2016) and includes parameters like solar radiation, temperature, humidity, and wind speed. The project involves data wrangling, feature selection, and engineering, followed by prediction using XGBoost and a MultiLayer Perceptron model.

# Dataset
The meteorological data, sourced from the HI-SEAS weather station, is crucial for understanding solar irradiance. Fields include date, time, and numeric/text data. The units range from watts per meter^2 for solar radiation to degrees Fahrenheit for temperature.

# Project Flow
Data Wrangling: Splitting and extracting relevant features such as month, day, year, and time. Creating a target dataset with only the radiation column.

Feature Selection: Utilizing correlation matrix, SelectKBest method, and Extra Tree Classifier to choose relevant features for prediction.

Feature Engineering: Applying transformations like BoxCox, Log, Min-Max, and Standardization to enhance feature effectiveness.

Data Preparation: Standardizing and splitting the data into training and testing sets.

Modelling: Implementing XGBoost for initial predictions and a MultiLayer Perceptron model for a comprehensive approach.

# Usage
Clone the repository.
Follow the step-by-step instructions in the provided Jupyter notebook.
Explore insights gained from feature selection, engineering, and model predictions.

Feel free to contribute, adapt, or use this project to enhance solar irradiance predictions. Dive into the world of renewable energy forecasting with machine learning! 
