## House-Price-Predictor

A machine learning project to predict house prices using Linear Regression and Random Forest Regressor models. This project demonstrates data preprocessing, model training, evaluation, and comparison of predictive performance.

# Dataset

The dataset used contains housing data with features like:
longitude
latitude
housing_median_age
total_rooms
total_bedroom
population
households
median_income
median_house_value
ocean_proximity
bedroom ratio
household room

Used dataset from Kaggle https://www.kaggle.com/datasets/camnugent/california-housing-prices

1. longitude: A measure of how far west a house is; a higher value is farther west
2. latitude: A measure of how far north a house is; a higher value is farther north
3. housingMedianAge: Median age of a house within a block; a lower number is a newer building
4. totalRooms: Total number of rooms within a block
5. totalBedrooms: Total number of bedrooms within a block
6. population: Total number of people residing within a block
7. households: Total number of households, a group of people residing within a home unit, for a block
8. medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
9. medianHouseValue: Median house value for households within a block (measured in US Dollars)
10. oceanProximity: Location of the house w.r.t ocean/sea
11.bedroom raito = total_bedroom/total_rooms
12.household room = households/total_rooms

# Results

Model performance on the test dataset:

* Linear Regression R² Score: 0.6665590271750416
* Random Forest R² Score: 0.8208801326616076

The Random Forest model performed better because it can capture non-linear relationships in the data.


I  working with the Hyperparameter tuning with Random Forest Model(there in the code). Results yet to be updated.
