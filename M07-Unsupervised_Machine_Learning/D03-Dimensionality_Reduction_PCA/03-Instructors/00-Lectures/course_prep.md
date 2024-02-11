# Dimensionality Reduction

This course is about dimensionality reduction, and more specifically PCA.

This course is often challenging for the students because of the algebra that is needed to explain in detail how PCA works, reassure them by insisting mostly on the intuition behind PCA which is actually quite simple, picking and axes along with the data has the most variance.

# Lectures

## 01-Understand_PCA - 60 min

This course explains the theory on PCA. Start by showing an example in two or three dimension that you reduce to one dimension only by projecting the data points onto the axes with the most variance.
Then you may introduce more technical aspects of matrix diagonolisation useful to find the principal components.
Then insist a lot on the main two usecases for PCA which are:
* Getting a faithful apporximation of the data with two or three principal components so data may be easily visualized
* Reducing the number of variables while keeping a vast majority of the information, this will let machine learning algorithms run much faster on your data while losing a minimum amount of performance.

## 02-Code_PCA - 30 min

This lecture invites the sutents to code a PCA using sklearn. 

The main thing to is tell the students that PCA is the same type of python object than StandardScaler. In terms of code it worth noting that PCA may be included in a broader sklearn pipeline, and therefore the dimension reduction characteristic may be cross validated.

# Exercises

## 01-House_prices_reduction - 30 min

This dataset lists houses with their sales price.
The goal of the exercise is to try and get some general understanding of the data through PCA and visualization.
This is a great opportunity to teach the students how to link the PCA with the original variables in order to be able to interpret the final visualisation.

## 02-Noise_cancellation - 30 min

This exercise shows the other PCA usecase, where we reduce the dimension of the dataset in order to train ML models much faster with almost equivalent results.
Students often focus a lot on the general performance of the models they build, they think higher performance is always better, this is not necessarily the case, machine learning is used in contexts where ressources may be limited, where interpretability may be important, where the volume of data may be really high, and so on. Dimensionality reduction may be life saving in certain contexts because it can really save you a lot of time.