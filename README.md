# Diamond Price Prediction: Exploratory Data Analysis and Regression Models

This repository contains an analysis of the Diamond dataset from 2022. The goal is to predict diamond prices using various regression models.

## Table of Contents
1. Introduction
2. Data Exploration
3. Regression Models
4. Conclusion

## Introduction
The dataset contains information about various attributes of diamonds such as carat, cut, color, and clarity, etc. The aim is to predict the price of a diamond based on all the related attributes and maximize the model's accuracy.
You can find two Jupyter Notebook files, one named EDA_and_LinearModel, and the other named polynomialRegModel. The former contains EDA and Linear Model, and the latter contains code for the Polynomial Regression Model.

## Data Exploration
Our journey begins with an exciting phase of Exploratory Data Analysis (EDA). We'll dive deep into the data, visualizing the distributions and identifying any outliers. We'll plot category counts on a graph, revealing how many diamonds belong to specific categories in the object type columns. 

But that's not all! We'll also perform feature scaling to ensure our models can handle the data effectively. This step is crucial as it helps to normalize the range of independent variables or features of the data.

## Regression Models
With our data prepared, we'll embark on the next phase of our journey: building regression models. We'll use:

1. **Multi Linear Regression**: A model that considers multiple input features to predict the price of diamonds.
2. **Ridge Regression**: A model that shines when there is multicollinearity in the data, and helps in reducing the conditions of overfitting. It uses the L2 regularization technique.
3. **Lasso Regression**: A model that uses the L1 regularization technique, which can lead to zero coefficients i.e., some of the features are completely neglected for the evaluation of output.
4. **ElasticNet Regression**: A model that combines the strengths of Ridge and Lasso Regression techniques. It uses both L1 and L2 regularization.
5. **Polynomial Regression**: A model that comes into play when the relationship between the independent and dependent variable is non-linear.

## Conclusion
will compare the accuracy scores and mean square errors of all the models. Our main aim is to maximize the accuracy score and reduce the mean squared error (Not to make it equal to 0 - leads overfitting).
Later will see that polynomial regression gave us the best accuracy results.

