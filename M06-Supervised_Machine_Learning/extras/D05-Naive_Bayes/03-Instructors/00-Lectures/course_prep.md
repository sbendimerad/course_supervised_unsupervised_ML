# Course Preparation 

The purpose of this course is to learn about a very light model efficient on relatively small data but still non-linear : Naive Bayes.

Learning about this model will also serve as an excuse to refresh the students' memory or let them learn about elementary probability theory. It is important for them to understand the basics of probabilties since almost all machine learning models are built on prabilities, and now is the perfect time to make sure they do.

## Naive Bayes - 2 units min

In this lecture, you will be introducing the naive bayes model. The major difficulty of this lecture is to make the students see past the calculus leading to the model, but rather understand what it means in terms of predictions and how strong the fundamentals hypothesis are.
At the end of the lecture the students need to be confortable with :
* random variable
* experiment
* independent variables
* dependence vs. correlation
* joint probability
* conditional probability
* Bayes Theorem

The main take away from this lecture is that naive bayes model is a very simple non linear model that can perform well on small datasets. It naturally has a high bias and low variance. 
    
## Exercise - Handle diabetes with naive bayes 1 units

This exercise can be decomposed into three different parts :

### 1 classical approach
The students will pay attention to the data they are working on and you have to make them realize that many incoherent values are present in the dataset. The first approach to this exercise will ask the students to remove from the observation sample all data that is not one hundred percent correct and complete.
The variables will not be modified in order to improve the model.

### 2 Discretization approach
In this second step, the stuendts will have to learn how to discretize continuous variables in a very efficient way, identify the discretization order they wish to apply on each variable and then run a new model that deals with categorical variables.

### 3 Imputation approach
We started the exercise by removing all sketchy observations, we will now try and treat all suspicious values in the data as if they were missing and find new values for them that we will infer from the rest of the legitimate observations.

## Project - A toi de jouer Aurélie :)
