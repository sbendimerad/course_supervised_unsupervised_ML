# Kmeans

This course introduces a clustering technique: Kmeans.
A slide deck is at your disposal for this course, use it to help you structure the lecture.

# Lectures

## 01-Understand_KMeans 45 min

Here you'll introduce the main notions surrounding Kmeans. Make sure the students are aware of these key aspects:

* What is clustering, and when is it useful:
    * typical examples are: clustering shop customers, people on social media depending on what they look at, making groups of similar people on any content platform (any situation where there is not any measurement of a target variable)
    * clustering always consists in establishing groups of data points depending on a certain measure of distance between them (the choice of the distance and how to use it is crucial)
* Kmeans forces you to pick the number of clusters you want to create
* General rules of thumb to pick the number of clusters
* Sensitivity to initial positions of clusters centers
* What's most important is to be able to interpret the clusters, link them to some concrete reality

## 02-Code_KMeans 45 min

This lecture introduces how to form clusters using Kmeans.

It will also teach the students how to find the theoretically best number of clusters using the elbow method (looking at the inertia plot), and the silhouette score (how isolated from each other are each of the points in clusters)

In terms of the silhouette score, present with a schema four different forms of clusters:
* A concentrated and isolated cluster: high silhouette average, low silhouette variance
* A concentrated and not isolated cluster: low silhouette average, low silhouette variance
* A dispersed and isolated cluster: high silouhette average, high silouhette variance
* A dispersed and not isolated cluster: low silouhette average, high silhouette variance

Concretely, to interpret the clusters the students may:
* analyse the characteristics from the cluster centers (make sure that the cluster centers are resonnable representants from the cluster's distribution)
* Use PCA to be able to visualize the clusters (or directly visualize if there are not too many variables)

Note that in general Kmeans becomes harder and harder to interpret when the number of variables grows (first because distances between data points grow a lot with the number of variables, and secondly because of the number of metrics to look at)

# Exercises

## 01-Know_your_customers 30 min

This exercise shows a classic use of Kmeans for clustering a client base based on their consumption characteristics, the important part of the exercise are:
* determining the number of clusters needed
* interpreting the clusters

## 02-Digit_Recognition_KMeans 30 min

This exercise attempts to create clusters with Kmeans to see how close they end up being compared to the available target variable for handwritten digits. This should give some perspective on the relative reliability of Kmeans clustering.