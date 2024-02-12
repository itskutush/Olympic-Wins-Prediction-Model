
# Olympic Win Prediction Model


Data from the previous year Olympic results is used to predict the future wins of the countries .

## Approach
Dataset 'teams.csv' contains data of the Olympic Wins of all countries till. The dataset has been divided on a 80-20 basis to train and test it . Training data: All the wins scored by the participating countries in the years < 2012.Testing data: Predicting the wins of the countries participated in the Olympics from 2012 and later .First the data is indentified and cleaned. The coloumns which are not required can be filtered out .Then using Linear Regression we can predictions. Then using Mean Absolute Error , the errors are calculated b/w the real and the real values . This gives a clear idea onn the accuracy of out training model and gives insights how the model can be improved.

Accuracy %age : 78.85780495412234

## Linear Regression
Linear regression analysis is used to predict the value of a variable based on the value of another variable. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable.LR haelps to make predictions make easily. It is a scientifically proven and reliable way to predict the future.
## Error Metric
 ![Screenshot 2024-02-12 224931](https://github.com/itskutush/Olympic-Wins-Prediction-Model/assets/89831977/50f31739-3c4e-4392-a7df-76b4f2e264d3)
                

Mean absolute error (MAE) is a measure of errors between paired observations expressing the same phenomenon. Mean absolute error is a popular metric because, as with Root mean squared error (RMSE), the error value units match the predicted target value units. Unlike RMSE, the changes in MAE are linear and therefore intuitive. MSE and RMSE penalize larger errors more, inflating or increasing the mean error value due to the square of the error value. In MAE, different errors are not weighted more or less, but the scores increase linearly with the increase in errors. The MAE score is measured as the average of the absolute error values. The Absolute is a mathematical function that makes a number positive. Therefore, the difference between an expected value and a predicted value can be positive or negative and will necessarily be positive when calculating the MAE.


