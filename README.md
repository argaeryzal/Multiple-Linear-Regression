# Multiple Linear Regression Model
Analyze 50 Companies it is Most Interested in Investing and wants to see if there's any correlations between profit and the months that have been spent on different expenses
## 1. Importing the Libraries
- Numpy
- Matplotlib
- Pandas
## 2. Importing the Dataset
- Read the dataset using pandas tool
- x = dependent variable
- y = independent variable
## 3. Encoding Categorial Data
Encode the "State Variable" which is string values, make it to numerical values using OneHotEncoder
## 4. Splitting the Dataset into the Training Set and Test Set
- Import class train_test_split from sklearn
- x_train, x_test, y_train, y_test using train_test_split and make 20% of the dataset to perform testing
## 5. Training Multiple Linear Model on The Training Set
- Import class LinearRegression form sklearn
- Make an object called Regressor
- Regressor.fit the x_train and y_train
## 6. Predicting the Test set Result
- Make an object called y_pred, which is regressor predict from x_test
- Numpy set printoptions, precision is 2
- Reshape the vertical variable result, make it horizontal
## 7. Making Single Prediction
Predicting each variable values
## 8. Getting the Final Linear Regression Equation
- Find the regressor coeficient
- Find the regressor intercept
