
# Predicting House Prices with linear regression Model

In this project, we will use the `USA_Housing.csv` dataset to build a machine learning model that predicts the price of a house based on its features.

## Dataset

The dataset contains the following columns: 

- Avg. Area Income: Average income of residents of the city where the house is located.
- Avg. Area House Age: Average age of houses in the same city.
- Avg. Area Number of Rooms: Average number of rooms for houses in the same city.
- Avg. Area Number of Bedrooms: Average number of bedrooms for houses in the same city.
- Area Population: Population of the city where the house is located.
- Price: Price at which the house was sold.
- Address: Address of the house.

## Goal

Our goal is to build a machine learning model that can accurately predict the price of a house given its features. We will train our model on the training set using linear regression algorithms and evaluate its performance on the test set.

## Tools Used

We will be using Python 3 with the following libraries:

- Pandas: For data manipulation and analysis
- NumPy: For numerical operations
- Scikit-learn: For machine learning modeling and evaluation
- matplotlib.pyplot
- seaborn

## Steps

1. Load and explore the dataset
2. Preprocess the data
3. Divide the data into training and testing sets
4. Train and evaluate linear regression model
5. Choose the best performing model and make predictions on new data

Please refer to the `predicting-house-prices.ipynb` notebook for the detailed implementation of the above steps.


## Conclusion

In this project, we built a linear regression model that can accurately predict the price of a house based on its features. We achieved this by preprocessing the data, dividing it into training and testing sets, training and evaluating linear regression model. Our final model achieved an R-squared score of `0.917` on the test set, indicating that it can explain `91.7%` of the variability in the target variable.
