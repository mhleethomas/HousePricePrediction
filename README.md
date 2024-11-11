This project uses a dataset of house sale prices from King County, which includes Seattle, WA, to predict home prices based on various features. The dataset comprises sales of homes between May 2014 and May 2015 and includes 21 variables capturing various property characteristics. The goal is to develop a predictive model to estimate house sale prices using these features, evaluating the model's performance based on root mean square error (RMSE) of the log-transformed prices.

Dataset Overview

The dataset includes the following columns:

id: Unique identifier for each home sold.
date: Date of sale.
price: Sale price of the home (target variable).
bedrooms: Number of bedrooms.
bathrooms: Number of bathrooms (0.5 indicates a half-bathroom).
sqft_living: Square footage of the interior living space.
sqft_lot: Square footage of the land lot.
floors: Number of floors.
waterfront: Binary variable indicating if the property has a waterfront view.
view: Index from 0 to 4 indicating the quality of the property's view.
condition: Index from 1 to 5 indicating the condition of the property.
grade: Index from 1 to 13 assessing building quality, where higher values represent better construction and design.
sqft_above: Square footage of above-ground living space.
sqft_basement: Square footage of basement space.
yr_built: Year the house was built.
yr_renovated: Year of the most recent renovation.
zipcode: Zip code of the property.
lat: Latitude of the property location.
long: Longitude of the property location.
sqft_living15: Average living space of the 15 nearest neighbors.
sqft_lot15: Average lot size of the 15 nearest neighbors.
Project Goals

The primary objective of this project is to predict house sale prices in King County. To achieve this, we will:

Data Preprocessing and Cleaning: Check for missing values, handle anomalies, and ensure the dataset is ready for modeling.
Feature Engineering: Apply transformations (e.g., log transformation) to reduce skewness or normalize distributions, encode categorical features, and examine potential feature interactions.
Feature Selection: Identify and retain features most relevant to predicting house prices.
Model Selection and Training: Compare various regression models, evaluate their performance using RMSE on log-transformed prices, and select the best-performing model.
Evaluation and Interpretation: Analyze the model's predictions, assess feature importance, and document any significant findings and learnings.
Evaluation Metric

Root Mean Square Error (RMSE) between the log-transformed predicted values and log-transformed actual prices.
This metric ensures that prediction errors for both high- and low-priced houses are weighted equally.
Steps to Complete the Project

Data Preprocessing:
Handle missing values and outliers.
Apply necessary feature transformations (e.g., log transformation for highly skewed features).
Feature Encoding:
Convert categorical variables to numerical formats as needed (one-hot encoding or ordinal encoding).
Feature Selection:
Identify and select the features most correlated with the target variable.
Model Building and Selection:
Experiment with models such as Linear Regression, Decision Trees, Random Forest, Gradient Boosting, and others.
Use cross-validation to select the best-performing model based on RMSE.
Result Analysis:
Interpret model outputs and examine the importance of each feature.
Compare model performance and discuss potential limitations or biases in predictions.
Results, Findings, and Learnings

The project will document:

The model that performed best based on the evaluation metric.
Key features influencing house prices.
Insights or patterns identified in the data, such as the relationship between house attributes and price.
Lessons learned throughout the analysis, including model limitations and possible improvements for future work.
