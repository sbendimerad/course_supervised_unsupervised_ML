# Course Preparation 

In this course, we introduce Logistic regression for classification problems with either a binary target variable or an ordinal categorical variable.

The goal for the students is to understand how to prepare their data for these models, interprete their results both in terms of performance and in terms of understanding the impact of each variable on the target variable.

## Lecture logistic regression - 90 min

Remember that even though this lecture contains mathematical notations and theory, the main goal of the lecture is to give the students tools to understand the intuition of how logistic regression works, all essential aspects will be covered in the different exercises so do not get too caught up into explaining the mathematical theory. The main points you need to cover while giving this lecture are the following :

* what is a classification
* what similarities between linear and logistic regression
* false positive, false negative
* Evaluation metrics :
    * accuracy
    * recall
    * precision
    * F1-score
* ROC Curve
* AUC

## Logistic regression template - 45 min
This template shows an implementation of univariate and multivariate logistic regression, with performance evaluation. There is no particular difficulty as the data and the code are very similar to the previous templates, but it may take up to 1 hour to go through all the cells, as there are quite a lot of new classes and functions. Don't forget to show the students where to find these classes' descriptions in scikit-learn's documentation.

## Exercise - First classification - 80 min

This exercise focuses on logistic regression and understanding from a concrete example how it works. 

It covers the following aspects :
* LogisticRegression model
* predict vs predict_proba
* ROC curve
* confusion_matrix
* cross_val_score
* plot_decision_boundary


## Exercise - Vino Verde - 40 min
This exercise is an application of logistic regression to a problem where the target variable is categorical ordinal and also difficult to predict. It will lead the student to repeat most of the command lines needed in the other exercise, however more thinking and interpretation will be needed to reach the end of the exercise.
This exercise introduces some new ideas, such as simplifying some variables for better visualization and interpretation, feature engineering etc...

This exercise might appear more difficult to some of the students. They may not be able to finish it before 4pm. If too many students are stuck, just go through it as a live coding in front of the class. You can also ask for volunteers among the students to make the correction.

## Project Conversion rate challenge - 30 min
Save at least 30 minutes to introduce the Conversion rate challenge. This project is special because it mimics a Kaggle challenge. The students might have a lot of questions about the rules and organization. You can follow these steps to make an introduction:
* Quick overview of Kaggle's website, and how to participate to a challenge
* Conversion rate challenge: the dataset, the metrics used for the leaderboard, the organization, the deadline for last submit
* Conversion rate challenge template: give them a quick overview.

After 4pm, the students will have to take some time to read the conversion rate challenge template, make sure they understand the different steps and try to make some changes in the model/features to improve the baseline score.

In the next days, you or the TA will regularly update the leaderboard with the new predictions sent by the students. A script is a available in the "instructor" part of the project's material to update the leaderboard.
--- 

Thank you for helping us bring our student to the next level in their career! Help us improve by giving us any feedback on the session on discord, and/or on the content as a [github issue](https://github.com/JedhaBootcamp/FULL_STACK_12_WEEK_PROGRAM/issues)
