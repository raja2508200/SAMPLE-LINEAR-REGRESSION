# SAMPLE-LINEAR-REGRESSION

Importing Libraries: The code imports the necessary libraries: pandas for data manipulation, numpy for numerical operations, and linear_model from sklearn for building the linear regression model.

Loading Data: The code reads a CSV file named 'homeprices.csv' into a DataFrame df.

Handling Missing Values: It checks the median of the 'rooms' column, then fills any missing values in the 'rooms' column with this median value.

Building the Model: The code initializes a linear regression model using linear_model.LinearRegression(). It then trains the model (reg.fit) using all columns except 'price' as features and 'price' as the target variable.
