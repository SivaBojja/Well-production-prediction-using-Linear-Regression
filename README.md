# Well-production-prediction-using-Linear-Regression

The production of a well is predicted by  linear regression model and this model is compared with new trained model using reduced features and also a model with different features. The metric used here is Root Mean Square Error.

Using “China_Oilfield.csv” production data, where (y) was given as a function of: 
X1 = The total number of wells producing 
X2 = Wells coming online that were shut 
X3 = New wells added 
X4 = The injected water volume last year 
X5 = The oil moisture content of last year 
X6 = The oil production rate of last year 
X7 = The recovery percent of last year 
X8 = The oil output of last year 

The following activities are performed:

1. Perform data exploration 

2. Train a linear regression model using the 8 variables and data from the year 1983-1999. Predict the solution from the year 2000-2006. Compare the actual and the predicted solutions. 

3. Use the following four variables only and repeat the model training. Compare the error between using 8 variable model and 4 variable model to see which model is better. X2 = Wells coming online that were shut X4 = The injected water volume last year X5 = The oil moisture content of last year X7 = The recovery percent of last year

4. Use the 4 variable model from the previous training data and a new model trained from the “China_Oilfield_2.csv” data from the year 1983-1999 to predict the production between 2000-2006 and compare the error to see which model performs better
