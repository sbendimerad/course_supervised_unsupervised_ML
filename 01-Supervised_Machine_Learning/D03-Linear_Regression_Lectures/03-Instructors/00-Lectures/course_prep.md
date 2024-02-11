# Course Preparation 

In this course, we introduce Linear models for regression.

The goal for the students is to understand how to prepare their data for these models, interprete their results both in terms of performance and in terms of understanding the impact of each variable on the target variable.

This lecture contains a lot of theory that you do not necessarily need to get into too deeply (in particular the "OPTIONAL" contents), the main objective is for the students to understand how to apply these models on data and interpret the results. The important notions you need to cover giving this lecture are the following :

* what is linear regression
* target variable
* explanatory variables
* coefficients
* intercept
* predictions
* residuals
* theoretical assumptions for applying linear regressions
* loss function
* ANOVA
* R square / R square adjusted
* model selection process

## Lecture Linear Regression - 45 min

This lecture is an introduction to the theoretical aspects of univariate and multivariate linear regressions. On top of the mathematical expressions, it's important to rely on concrete and visual examples. After this introduction, the students must be familiar with the meaning of the different terms (target/explanatory variables, coefficients, etc...) as well as the asumptions behind linear regression.

For some of the students, it may be the first time they encounter some of the mathematical symbols that are used. If it's the case, take some time to explain the meaning of these symbols.


## Lecture Performance assessment and feature selection - 30 min

In this lecture, some metrics for performance assessment are introduced. The mathematical expressions are introduced but it's also important that students understand the *meaning* of these metrics and why they are relevant in the case of linear regression.

In the end of the lecture, some model selection strategies are mentionned. However, it's not necessary to take more than 5 minutes on the explanations, as the students will have the opportunity to implement some model selection algorithms during the exercises/projects of the next days.

## Linear regression template - 60 min

This template is quite dense, at least 1 hour is necessary to get through all the steps:
* EDA before linear regression
* univariate and multivariate linear regressions with preprocessings
* performance assessment
* extracting and interpreting the model's coefficients


## Exercise - California Housing Market - 60 min

This exercise focuses on linear regression. It covers the following concepts :

* data visualization
* splitting data into train and test
* analysing model coefficients 
* understanding feature importance
* evaluating the model

This exercise is quite similar to the linear regression template, so every student should be able to make it to the end. If the students are not yet very fluent with pandas/sklearn, it may be necessary to take more than 1 hour to go through the full exercise + correction.

## Exercise - Feature engineering and feature selection - 60 min

This exercise deals with same dataset (California Housing Market), but this time the students are asked to make some feature engineering to include non-linearities into the regression model. As the number of variables will increase a lot, the students are also asked to implement a forward selection method by using scikit-learn's SequentialFeatureSelector. In the end of the exercise, the students are guided to use an API so as to extract useful information from the GPS coordinates. However, the calls to the API are quite time-consuming. That's why it's done in the end by keeping only 150 rows of the initial dataset.

This exercise is quite difficult because it goes way beyond what the students learnt in the morning. If the students are already struggling with the first exercise, feel free to tell them that this second one is optional.

## Project - Walmart Sales - 20 minutes
For the end of the afternoon, the students can apply what they learnt about regression models to complete the part 2 of the Walmart Sales project.
--- 

Thank you for helping us bring our student to the next level in their career! Help us improve by giving us any feedback on the session on discord, and/or on the content as a [github issue](https://github.com/JedhaBootcamp/FULL_STACK_12_WEEK_PROGRAM/issues)
