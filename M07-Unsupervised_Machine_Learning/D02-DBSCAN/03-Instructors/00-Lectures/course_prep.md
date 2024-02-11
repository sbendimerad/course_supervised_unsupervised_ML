# DBSCAN

This course introduces a new clustering technique that creates clusters of arbitrary shapes for spatial data.

This day should be quite light, so this is a good opportunity to get the students working on their unsupervised learning projects.

# Lectures

## 01-Understand_DBSCAN 45 min

Here you will introduce the theory behind the DBSCAN clustering method, what's important for the students to remember is:
* what's a core point, a border point, and noise
* the notion of radius of the neighborhood and minimum number of neighbors
* the fact that DBSCAN is well suited only for spatial data
* DBSCAN is noise resistant, it does not have to place each data point in a cluster

## 02-Code_DBSCAN 30 min

This is the demo of how to use DBSCAN with sklearn
One prectical piece of advice you may give the students is how to pick the radius and min number of neighbors relatively to the observed data. In clustering, what matters is that the cluster make sense. For example if you think of a usecase where you have data from people's location when visiting a store at different times of the day, you may want to know where the clients aglutinate to either change the store's layout, or put your most popular products in those spots, for that you need to choose what radius around a given client makes a good neighborhood, and how many clients in a given radius make a high customer concentration from your standpoint, maybe it's 10 customers in a radius of 2m from one another that form a cluster.
The main logic being that it is density based.

# Exercises

## 01-911_emergencies 45 min

The students are given a dataset of 911 emergency interventions of different kinds with their geolocation.
The goal of the exercise is to create different clusterisations using DBSCAN to understand where emergencies most often happen.
Encourage the students to dig further, for exemple by searching for the location of the emergency services in the area to figure out whether they should rather be located elswhere, are some area underserved etc...