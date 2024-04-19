# Linear-Regression

## What is a linear regression
An equation which relates a dependent variable and one or more independent variables, and fits a linear equation to the observed data is called Linear regression. The aim is to find the line that fits best by minimizing the differences between what has been observed in fact and what would be predicted by the model. It is therefore applied in diverse fields such as economics, finance, biology, social sciences among others for analyzing trends, predicting them and comprehension of relationships between variables for forecasting purposes. Statistical analysis as well as predictive modeling supports these contexts as it is assumed that there is a straight line association amid these factors at all times. Linear regression underlies statistical analysis and predictive modeling because it involves inferring a relationship between two or more sets of observations on different measures

## Why is it often used in ML 
Linear regression is often made use of in artificial intelligence for numerous factors. First of all, its simpleness makes it simple to recognize together with carry out especially for novices in the area. In addition direct regression functions as a standard design for even more complicated formulas supplying a criteria for contrast. Furthermore it can deal with both mathematical as well as specific information making it flexible for different kinds of datasets. Direct regression likewise supplies interpretable outcomes, enabling experts to recognize the influence of various variables on the result. Finally, its computational effectiveness makes it possible for fast training plus forecast on big datasets making it an effective option for lots of artificial intelligence jobs.

## How to make a linear regression 
To make a linear regression we will use other libraries because to make it easier. We will use matplotlib, pandas and numpy which are very popular python librarues when it comes to ML:
To develop a linear regression model using matplotlib, pandas, and numpy, we first import these libraries. Then, we load our data with pandas and split it into features \(X\) and the target variable \(y\). Next, we compute the coefficients \(\beta\) using the normal equation:

\[
\beta = (X^T X)^{-1} X^T y
\]

After that, we visualize the data and regression line using matplotlib. Finally, we make predictions on new data using the learned model. This approach allows for a straightforward implementation of linear regression for predictive modeling tasks in Python.
