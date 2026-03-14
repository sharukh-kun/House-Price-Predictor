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

# Results

Model performance on the test dataset:

* Linear Regression R² Score: 0.64
* Random Forest R² Score: 0.82

The Random Forest model performed better because it can capture non-linear relationships in the data.
