# Topic Modeling

The main thing that students need to understand is that topic modeling is nothing more than PCA applied to a dataset where the columns represent the importance of certain words, for a term frequency matrix for example, or a TfIdf matrix.

At the end of this class, you should have some time to let the students take the quizz and then go through the solution together before helping them with their projects.

# Lectures

## 01-Understand_LSA - 60 min

This course introduces the theory behind LSA, make sure to make the connection with PCA because they both rely on the same diagonalisation methods.
The topics will be new variables that are combinations of original variables (the word importances), because it uses the same process as PCA the first will contain the most variance, while the other will make up for less and less of the total variance.

Topics are not necessarily directly interpretable, what could be interesting however is to run some clustering after that topic modeling is done to see how the different texts in the corpus are clustered and then interpret the clusters.

## 02-Code_LSA - 30 min

This demo shows the student how to execute topic modeling in practice.

# Exercises

## 01-Topic_modeling - 60 min

The exercise shows topic modeling applied to a corpus of news articles.
If there is time, run some clustering on the texts using the topics, you should see that a lot of the original labels for the texts will find themselves in the same clusters!