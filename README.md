# Capstone-Project
Notes for my Ryerson Project



Restaurant Reviews

Introduction

Data from restaurant reviews are difficult to assimilate because they have been collected from different entry points throughout the internet. I have found a source that contains several data sets that attempt to compare users from different American cities to users in Chicago. The datasets were downloaded from the Entrée Chicago restaurant website and was created to give tourists a comparison to their favorite local restaurants to places they may visit while they’re in Chicago.  I will use these data sets to create a user-based collaborative recommendation engine. 


Literature Review

There are 2 main papers that I reviewed for this project.  The first is a paper called Data Mining Methods for Recommender Systems by Xavier Amatriain, Alejandro Jaimes, Nuria Oliver, and Josep M. Pujol. It covers the whole process of how to create a recommendation system from scratch.  It shows the framework of all the steps that are involved including data mining, dimensionality reduction, and knowing which similarity measures to use and why.
The second paper is by Michael J. Pazzani called A Framework for Collaborative, Content-Based and Demographic Filtering. I used this paper to help me understand the difference between collaborative and content-based recommendations and how the dataset should be constructed before using similarity measures


Dataset

The datasets were downloaded from the UCI Machine Learning Repository.  The original source of the data is from the Entrée Chicago Recommendation Data Set. I will be using all of the individual attributes used to describe the restaurant ratings. There are 50672 instances collected from 35175 web hits. The data is broken into 8 datasets from American cities- Atlanta, Boston, Chicago, Los Angeles, New Orleans, New York, San Francisco and Washington DC. 1 data set included a description of all the features. 12 datasets includes the user ratings.


Approach
.
 
Step 1: Transform restaurant data into binary matrix

Step 2: Categorize feature dataset

Step 3: Build User-based collaborative filtering system


Step 4: Evaluate the model
