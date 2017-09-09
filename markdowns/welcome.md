# Machine Learning with Java - Part 2 (Logistic Regression)

Regression analysis is a predictive modelling technique which is used to investigate the relationship between the dependent and indepedent variable(s).It is the important tool for modelling and analysing the data.From the data points we draw the curve or the line and we try to fit it in such a manner that the difference  between the distance between the data points to the curve or line is minimal.

In my last article , I have explained the liner regression with the sample data points. This article focuses on the Logistic regressions.


# Logistic Regression

Logistic regression is used when there are one or more indepedent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes).It requires large sample sizes because maximum likelihood estimates are less powerful at low sample sizes than ordinary least square.

The difference with linear regression is that, linear regression is output is continuous and not limited to number of possible.

Example: To determine whether we can play or not based on weather data .

# Types of Logistic Regression

The types of Logistic Regression are ,

1.<B>Ordinal logistic regression</B>

2.<B>Multinomial Logistic regression</B>

3.<B>Binomial Logistic regression </B>

# Ordinal logistic regression

If the values of dependent variable is ordinal, then it is called as Ordinal logistic regression. Ordinal regression is used to predict the dependent variable with ‘ordered’ multiple categories given one or more independent variables. 

Example : To predict the belief that the tax is too high , the dependent variable ranges from strongly agree to strongly disagree and the indepedent varibles are age, income. In this case, we wil use the ordinal logistic regression.


# Multinomial Logistic regression

Multinomial logistic regression is used to predict a nominal dependent variable given one or more indepedent variables.It is sometimes considered as extension of binomial logistic regression.

Example:To understand which type of drink consumers prefer based on location in the US and age.The dependent varibales woulb be type of the drink (Coffee, Soft Drink, Tea and Water) and the indepedent variables would be the nominal varibale ,localtion in US and the age (in years).

# Binomial Logistic regression

A binomial logistic regression, predicts the probability that an observation falls into one of two categories of a dichotomous dependent variable based on one or more independent variables that can be either continuous or categorical.This is often called as simple logistic regression.


Example:Let us predict , whether students will pass or not (i.e.,The dependent variables are Pass and Fail .) in their final exam based on the internal marks , assignment submission and few other independent variables. 

## Sample Training and Testing Data

<B> Training Data </B>  ![Train Diagram](LOGISTIC_TRAIN.PNG)  



<B> Testing Data </B>    ![Test Diagram](LOGISTICTEST.PNG.PNG)



<B> Notes </B>

An ARFF (Attribute-Relation File Format) file is an ASCII text file that describes a list of instances sharing a set of attributes. ARFF files were developed by the Machine Learning Project for the purpose of Weka machine learning software.

# Logistic Regression Demo

@[Logistic Regression]({"stubs": ["src/main/java/com/gg/ml/LogisticRegressionDemo.java"], "command": "com.gg.ml.LogisticRegressionDemoTest#test"})

# Explanation

