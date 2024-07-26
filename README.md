# House Prices Analysis Project with Machine Learning

## Overview
This project analyzes house prices data using Python and various libraries. We explore the data, visualize relationships between variables, and build different regression models to predict house prices.

## Data
The data is stored in a CSV file named `house_prices.csv`. It contains the following columns:

- **size**: Size of the house in square feet
- **bedrooms**: Number of bedrooms
- **age**: Age of the house in years
- **price**: Price of the house

## Steps Taken
1. **Data Cleaning and Preparation**:
   - Loaded the CSV file into a pandas DataFrame.
   - Ensured the file was loaded correctly by displaying the first few rows of the DataFrame.

2. **Exploratory Data Analysis (EDA)**:
   - Displayed information about the DataFrame to check data types and missing values.
   - Calculated summary statistics for the numerical columns.

3. **Visualizations**:
   - Visualized relationships between variables using pair plots with Seaborn and Matplotlib.

4. **Simple Linear Regression**:
   - Built a simple linear regression model to predict house prices using the size of the house.
   - Selected the size of the house as the feature and the price as the target.
   - Split the data into training and testing sets.
   - Created and trained the linear regression model.
   - Predicted the prices using the testing set.
   - Evaluated the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
   - Visualized the regression line along with the actual data points.

5. **Multiple Linear Regression**:
   - Built a multiple linear regression model using size, bedrooms, and age to predict house prices.
   - Selected multiple features (size, bedrooms, age) and the price as the target.
   - Split the data into training and testing sets.
   - Created and trained the multiple linear regression model.
   - Predicted the prices using the testing set.
   - Evaluated the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

6. **Polynomial Regression (Non-linear Regression)**:
   - Built a polynomial regression model to capture non-linear relationships between features and house prices.
   - Created polynomial features from the original features.
   - Split the data into training and testing sets.
   - Created and trained the polynomial regression model.
   - Predicted the prices using the testing set.
   - Evaluated the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Results
- **Simple Linear Regression**:
  - Mean Absolute Error (MAE): ...
  - Mean Squared Error (MSE): ...
  - R-squared: ...

- **Multiple Linear Regression**:
  - Mean Absolute Error (MAE): ...
  - Mean Squared Error (MSE): ...
  - R-squared: ...

- **Polynomial Regression**:
  - Mean Absolute Error (MAE): ...
  - Mean Squared Error (MSE): ...
  - R-squared: ...
