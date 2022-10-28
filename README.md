# Prediction using Supervised ML

Predict the percentage of an students based on the number of study hours.

The data was consist of two columns Hours and Percentages 

We have seen the Hours of Studies and Precentages are Highly Corelated to each other

Using the Simple Linear Regression Model to predict the future outcome

important two steps is to train and test the model

from Sklearn.model_selection import train_test_splits
x_train ,x_test ,y_train , y_test = train_test_splits(x,y,train_size=0.8, random_state=0)

from sklearn.linear_model import LinearRegression


