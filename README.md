# Simplified Netflix Challenge (research project)

This was the final project in Statistical Machine Learning course at HUJI (winter 2016/17).

## Authors: 
Eran Amar & Tomer Levy.

Keywords: Machine learning, KNN, random forests, elastic nets.

## About the project
As a final (research) project for the course ?Statistical Machine Learning? at HUJI, we attempted to tackle a simplified version of the 2009 Netflix Challenge. 
  We reviewed various Machine Learning techniques to create the best model possible for predicting user ranks. 
  We began with exploring the standard models individually, starting from k-nearest neighbors, random forests  and then Elastic nets. For each, we tried to build a non-trivial enhancement to the model. 
  Later, we composed those models in order to create stronger predictor.   

## Task Overview
The task is a simplified version of the Netflix Challenge from 2009. 
  The dataset is a matrix of rating of 12,931 users for 99 movies. 
  For each rating, there is also the corresponding date in which it was given (as a count of days since some unspecified epoch). The datasets were already split into Train and Test sets (10,000 users in the Train set). In both datasets, the first 14 movies were ranked by all the users, whereas other movies might have missing ranks (i.e. not all the users ranked them). 

The goal is to predict the rating of users from the Test set for a specific unseen movie - <em>Miss Congeniality</em>.  The rating for that move (which is the response variable) was given only for the training set.

Link the report file "netflix_report.pdf" inside the repo.