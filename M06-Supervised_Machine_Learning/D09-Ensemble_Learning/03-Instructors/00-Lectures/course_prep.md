# # Course Preparation

The purpose of this course is to learn about ensemble methods : Boosting, Stacking, and Voting/Averaging.

The main takeaway of this course would be for the students to understand how these ensemble methods work and what they can be useful for. Boosting is a method that improves a single predictor sequentially, Stacking is the process of predicting the target variable with a collection of first order predictors then use their predictions as explanatory variables for a second order model that hopefully will predict the target variable more accurately, Voting/Averaging is often used to create a model with more stable performance.

## Lecture - What is boosting - 45 min

This lecture introduces the general idea of boosting and illustrates it with two examples : Adaboost and gradient boosting mostly knwown through the popular librairy name XGBoost.

### Adaboost

The students will have to understand the following key points :

* what is a weak leaner

* what is a strong learner

* sequential aspect of boosting

* what does it mean to weight observations in a dataset

* what is a learning rate, what is its influence on the boosting

* how are the models aggregated in the end

### XGBoost

The students will have to understand the following key aspects :

* why is it relevant to train a model on another model's residus as target?

* how are the models aggregated in the end

### Boosting in general

* What's a margin for an observations

* how are the margins important to know if boosting will succeed or fail ?

* what's the difference between bagging and boosting?

* what is the objective of boosting

## Lecture - Voting Classifier and stacking - 15 min

This lecture introduces both stacking and voting/averaging.

### Stacking

The main ideas that the students need to understand here are :

* what are first order predictors

* what is the meta model

* why do we need to split the training data in order to avoid overfitting

* what kinds of models are best suited as first order predictors

* why should the first order predictions be as uncorrelated as possible

* what is the objective

* can stacking be compared to feature engineering

### Voting / averaging

Here is what the students should learn about voting / averaging :

* what kinds of models should be used for voting / averaging

* why do they need to be as uncorrelated as possible

* what is the goal of voting / averaging

## Lecture Summary of boosting - 10 min

Take 10 minutes to sum up the key concepts about ensembling and answer questions from the students.

## Lecture Ensemble methods template - 75 min

You can go through this template in live coding. Take also some time to show the different ensembling methods in scikit-learn's documentation.

## Exercise - Ensemble methods on Titanic - 150 min

This exercise is built on the Titanic dataset, that the students should know very well now. This allows to focus only on the different models and ensemble methods. The aim of this exercise is to compare the performances of different ensembling technics.

The cleaning and feature engineering is very similar to what was done in the "Advanced preprocessing" exercise of D01 (the lecture about preprocessing). Most of the students should now be fluent with that kind of code. However, if they get stucked to long, you can give them the solution so they can go directly to the part about models.

## Exercise - Ensemble methods AirBnB - 00 min

This exercise is optional. It's meant for students who would like to practice more on real-world data. This exercise is quite complete because it requires some exploration, cleaning, etc, before the model part.

## Project - Conversion rate challenge

Students can try to improve their scores in the leaderboard by using ensemble methods.

---

Thank you for helping us bring our student to the next level in their career! Help us improve by giving us any feedback on the session on discord, and/or on the content as a [github issue](https://github.com/JedhaBootcamp/FULL_STACK_12_WEEK_PROGRAM/issues)