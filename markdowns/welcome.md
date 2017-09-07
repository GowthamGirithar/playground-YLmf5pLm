# Machine Learning with Java - Part 2 (Logistic Regression)

Regression analysis is a predictive modelling technique which is used to investigate the relationship between the dependent and indepedent variable(s).It is the important tool for modelling and analysing the data.From the data points we draw the curve or the line and we try to fit it in such a manner that the difference  between the distance between the data points to the curve or line is minimal.

In my last article , I have explained the liner regression with the sample data points. This article focuses on the Logistic regressions.


# Logistic Regression

Logistic regression is used when there are one or more indepedent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes).It requires large sample sizes because maximum likelihood estimates are less powerful at low sample sizes than ordinary least square.

The difference with linear regression is that, linear regression is output is continuous and not limited to number of possible.

Example: To determine whether we can play or not based on weather data .

# Types of Logistic Regression

The types of Logistic Regression are ,

1.Ordinal logistic regression

2.Multinomial Logistic regression

# Ordinal logistic regression

If the values of dependent variable is ordinal, then it is called as Ordinal logistic regression. Ordinal regression is used to predict the dependent variable with ‘ordered’ multiple categories and independent variables. 


# Multinomial Logistic regression

# Logistic Regression Demo

@[Logistic Regression]({"stubs": ["src/main/java/com/gg/ml/LogisticRegressionDemo.java"], "command": "com.gg.ml.LogisticRegressionDemoTest#test"})

