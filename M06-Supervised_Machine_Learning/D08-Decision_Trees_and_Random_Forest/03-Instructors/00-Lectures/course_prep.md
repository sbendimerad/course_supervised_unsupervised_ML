# Course Preparation 

In this course, we introduce decision trees and random forest models. This is the first time that students will learn about a model that canbe used both for regression and classification, so it is very important to get that message across. It will also be the first non-linear model that we will introduce to the students, this is a great opportunity for the students to try and imagine the implications of choosing a decision tree or random forest for example when representing the prediction space.

The goal for the studentsis to understand how decision trees and random forests work in practice and apply these models on concrete data.

It is important for the students to understand that decision are entirely deterministic models once you've set the starting conditions (meaning data and hyper-parameters).

Another very important topic that you will discuss with the students is BootStrap, this technique consists in resampling the data by drawing with replacement, enabling the data scientist to artificially and randomly create new datasets that ressemble the original data without being strictly identical to it.

The concept of Bootstrap will lead you to talk about Bagging (Bootstrap Aggregating), the fact of generating a collection of samples by Bootstrap then training different instances of the same model on the samples and finally aggregating the predictions through weighted vote (classification) or weighted average (regression).

Finally you will show the students that a Random Forest simply consists in applying bagging to decision trees.

## Lecture Decision Trees - 40 min

In this lecture, you will be introducing decision tree. You will get into the detail of how decision trees are built so it is very important to be very clear and organised while presenting this topic since it's all about communicating the logic of building the decision tree.
The important points you will cover here are :

* construction algorithm in pseudo code
* Division criterion
    * Admissibility
    * Stopping criterion
    * Heterogeneity :
        * For regression (Y quantitative)
        * For classification (Y categorical)
* Overfitting and Hyper Parameters :
    * Tree depth
    * Min samples split
    * Min sample leaf

At the end of this lecture and before starting the first exercise it could be both amusing and relevant to get the students to try and graphically represent the decision boundary of a decision tree. This will make it possible for you to assess how much of the lecture they have actually understood.

## Lecture Random Forest - 40 min

This lecture explains the concepts of Bagging and how it can be applied to decision trees to create Random Forests.

### Bagging
The first aspect you will cover is bagging, the contraction of Bootstrap and Aggregating. To explain Bootstrap the main point is for the students to understand what is draw with replacement vs. draw without replacement and mkae sure they undertand why it makes it possible to create new samples that have very similar variable distribution as the original sample but still random.

The concept of aggregating often causes confusion among students, they are under the impression that we are combining the parameters of the models or that the trees are all merged together to form a mega tree, it is very important for the students to understand that it is much simpler than that and that all aggregating is doing is calculating either a weighted average on all predictions in a regression problem, and a weighted vote in case of a classification. Understanding this perfectly at this point will greatly benefit the students on the long run because many other techniques use aggregating and other variations of this concept.

### Random Forests
A random forest is just a special case of bagging applied to decision trees. What the students really need to understand is the two sources of randomness that make random forests better than decision trees :
* bootstrap on observations
* bootstrap on explanatory variables (concretely selecting a small number of features randomly for each decision tree in the forest)
Random Forests can have "smoother" decision boundaries than decision trees and generally perform and generalize better than decision trees. They are among the state of the arts models of classic machine learning.

## Lecture - Summary Decision Trees - 10 min
Take 10 minutes to make a recap. You can make it as a quizz for the students.

## Lecture - Summary Random forest - 10 min
Take 10 minutes to make a recap. You can make it as a quizz for the students.

## Lecture - Decision trees and random forest template - 40 min
As the students may now be at ease with this dataset and template, you can make this demo as a live coding by asking the students to tell you what to do next. Take also a few minutes to show them where to find the different classes related to tree models in scikit-learn's documentation, as well as the names and descriptions of the important hyperparameters.

## Exercise - Create a decision Tree - 150 min

This exercise has two main goals :
The first one is to introduce the students to using decision trees with sklearn, master the different hyper-parameters available to them in order to control the bias/variance trade-off. At the end of this exercise the students should be able to :
* use the DecisionTreeClassifier / DecisionTreeRegressor functions
* visualize a tree once it's fit through plot_tree and export_graphviz
* use the classification_report
* use the following hyper parameters :
    * max_depth
    * min_samples_split
    * min_samples_leaf
    * class_weight
    * criterion

At the end of the exercise, the students should be quite frustrated with the results obtained with their decision trees, they were promised a non-linear model that's able to fit almost any training data perfectly and suddenly it's impossible to model faithfully a very simple toy dataset. This is the second goal of the exercise, to help the students understand that even though decision trees are highly non-linear models, there are still very strong constraints on their decision boundary shape. The conclusion to this exercise should be that using non linear models and increasing the complexity of the models used is great, however what drives the performance of a prediction model is the data, if you increase the volume of data or achieve smart feature engineering, your results will often surpass any hyper-sophisticated model.


## Exercise - Uber fares - optional
This exercise is designed to give more practice to the best/fastest students. It's an interesting exercise as they have to make some smart feature engineering, compare linear and non-linear models and analyse the feature importances. However it's completely optional, so you're not supposed to make the correction in class. However, in case some students ask for it, you can take 10 minutes to give an overview of the steps of the correction and answer some questions.

## Project - Conversion rate challenge
For the end of the afternoon, the students can try to use decision trees and random forests to improve their scores at the conversion rate challenge.
--- 

Thank you for helping us bring our student to the next level in their career! Help us improve by giving us any feedback on the session on discord, and/or on the content as a [github issue](https://github.com/JedhaBootcamp/FULL_STACK_12_WEEK_PROGRAM/issues)
