# Course Preparation 

In this course, we introduce regularization, cross-validation and grid search for hyperparameter optimization.

The main objective of this course is to introduce the concepts of bias and variance and how to balance those two caracteristics in order to achieve the best fit for a machine learning model.

## Lecture Regularization - 40 min

This lecture's goal is to introduce both regularized versions of the linear regression models : Ridge and LASSO. The important concepts to get across to the students are the following :

### Ridge
* cost function
* bias vs. variance
* effect of regularization on the model and the coefficients
* when to use ridge

### LASSO
* motivation for LASSO (p >> n)
* effect on LASSO penalty on coefficients -> model selection
* underfitting and overfitting

### Bias vs. variance trade-off
* visual example of a underfitting
* visual example of overfitting
* there exist a balance between bias and variance

## Lecture cross-validation and grid search - 40 min

In this lecture, students learn how to use cross-validation to make a robust evaluation of a model's performance, and how to detect overfitting. As a solution to overfitting, the hyperparameter optimization by cross-validated grid search algorithm is introduced.

## Regularization and hyperparameter optimization template - 60 min

This template shows an example of implementation of regularized models, with cross-validated scores and how to tune the regularization strength by grid search. The code is not very long, but many new classes from scikit-learn are introduced. It's the opportunity to navigate into scikit-learn's documentation to explain:
* How the documentation is structured 
* How to find the descriptions of the models' asumptions
* How to know which are the hyperparameters names of a given model and their descriptions
* How to find examples of implementations

## Exercise - Regularization Ridge - 120 min

This exercise is about training a linear regression model on genetic data, with a lot of input features. It is quite long because the students are guided through the whole process:
* exploration
* preprocessing
* Ridge model with different values of alpha
* Lasso model with different values of alpha

The aim is to show the impact of a change in the regularization strength on a model's variance and its coefficients.

The entire afternoon may be necessary to deal with this exercise.

## Exercise - Handling overfitting - 20 min

This exercise deals with a real-world dataset that has some flaws and needs to be explorated and cleaned. The exercise is quite realistic, but the students are not supposed to be completely at ease with this kind of exercise now. It is meant to show them what they will do as junior data scientist. The bravest students can try to tackle the exercise on their own. Students that are less fluent in code can just have a look at the solution and try to understand all the steps. If you have some time, you can go through the exercise and briefly explain the different steps in class.

## Project - Walmart Sales - 10 min

During the second part of the afternoon, the students can apply what they learnt about regularization and hyperparameter optimization to tackle part 3 of the Walmart Sales project.
--- 

Thank you for helping us bring our student to the next level in their career! Help us improve by giving us any feedback on the session on discord, and/or on the content as a [github issue](https://github.com/JedhaBootcamp/FULL_STACK_12_WEEK_PROGRAM/issues)
