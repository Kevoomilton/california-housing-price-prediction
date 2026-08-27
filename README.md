# california-housing-price-prediction
Machine learning project for predicting California housing prices using regression models.

## Project Overview

This project develops machine learning models to predict median housing
values using demographic, geographic, and housing-related features from
the California Housing dataset.

## Objectives

The main objectives of this project are to:

- Explore and understand the housing dataset
- Handle missing values
- Perform exploratory data analysis
- Analyze relationships between features and house prices
- Apply data preprocessing techniques
- Perform feature engineering
- Train regression models
- Compare model performance
- Optimize the Random Forest model using GridSearchCV
- Evaluate the final model on unseen test data

## Dataset

The project uses the California Housing Prices dataset.

The target variable is:
median_house_value

The predictor variables include:

- longitude
- latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- ocean_proximity

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- KaggleHub

## Machine Learning Models

Two regression models were investigated:

1. Linear Regression
2. Random Forest Regression

The Random Forest model was further optimized using GridSearchCV
with 5-fold cross-validation.

## Feature Engineering

Additional features were created, including:

- bedroom_ratio
- household_rooms

Logarithmic transformations were also applied to selected highly
skewed variables.

## Model Evaluation

Model performance was evaluated using the R-squared score.

The final Random Forest model was selected after hyperparameter
optimization and evaluated on the held-out test dataset.

## Project Structure

housing-price-prediction/
│
-README.md
-HOUSE_PRICE_PREDICTION_PROJECT_1.ipynb
-requirements.txt
-data
-images

## Author

Kelvin Tibeshagosha Milton

Bachelor of Data Science
