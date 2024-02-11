# Course Preparation 

In this course, we introduce the students to the concept of data preprocessing with pandas and sklearn. It is important that the students understand general preprocessing guidelines that they can always go back to when in doubt. However it is a great time to continue giving them a sense of data intuition so they start interpreting the guidelines and adapt them to their data as opposed to applying mechanicaly.

## Introduction to Machine Learning - 30 min
This quick introduction is meant to bring some general context about machine learning. Some students may already know about the definitions of AI, Machine Learning, and Deep Learning. This lecture can be made as a "reminder" where the students are asked about what they think the different definitions would be. It's also the opportunity to answer general questions and mention some concrete examples of applications.

## What is preprocessing - 45 min

The goal here is to present the concept of structured data, it is not necessary to go into details, simply it's important that they understand that they will be focusing on structured data for now and that less structured and highly unstructured data exists and will be studied later.
Here's a short recap of the notions you need to cover in this part
* structured data / unstructured data
* quantitative variable : continuous / discrete
* qualitative variable : ordinal / nominal

Then you will dig into general preprocessing techniques :
* columns dropping
* rows dropping
* imputation of missing values
* nomalization
* encoding

Finally introduce the difference between the target variable and explanatory variables.

## Preprocessing with sklearn - 60 min 

This part consists in a demo where you will show how preprocessing works using sklearn on a toy dataset, it is important here not to hesitate to go into each command in the code in details and as much as possible bring the students to go through the code while you explain it and ask questions so everyone moves on to the exercises section with the deepest understanding of the commands.

The demo is organised in th following way :
1. Load data and basic exploration
2. Preprocessing with pandas 
3. Preprocessing with sklearn
4. Model training
5. Model prediction
6. Model evaluation

You should not go in as much details for points 4 to 6 as you would with 1 to 3 as these will be discussed in great details in the following courses. However they are important to demonstrate the efficiency of a well thought out preprocessing.

## Exercise : Preprocessing Titanic - 60 min
This exercise focuses on the famous Titanic dataset. It consists in applying the preprocessing guidelines explained during the course strictly and run all the way through the machine learning cycle once from data loading to model evaluation. It may not take more than 60 min, as the whole exercise can be solved by copying/pasting from the preprocessing template, with only very small changes.

This exercise aims reinforcing the students' understanding of preprocessing guidelines and how to apply them with code.

## Exercise : Advanced preprocessing - 60 min
This exercise adds a twist to the Titanic exercise where the students have to imagine different preprocessing strategies for this dataset that will let them extract more information to feed the model. A solution is suggested, but it would be interesting to see what ideas the students will come up with.

This exercise is a great way to start stimulating their ability to see beyond these guidelines and start developing data intuition.

## Project : Walmart Sales - 30 min
At the end of the exercise session, take 30 minutes to introduce the Walmart Sales project. During the free time with the TA, they can begin to apply what they learnt about EDA and preprocessing to solve the part 1 of the project.
--- 

Thank you for helping us bring our student to the next level in their career! Help us improve by giving us any feedback on the session on discord, and/or on the content as a [github issue](https://github.com/JedhaBootcamp/FULL_STACK_12_WEEK_PROGRAM/issues)
