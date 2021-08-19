# Udacity Data Scientist Nanodegree Project: Recommendations_with_IBM

## Project Overview

This project analyzes the interactions that users have with articles on the IBM Watson Studio platform, 
and the aim was to create a recommendation system that shows the articles that are most pertinent to a specific user.

## Table of Contents

1. [Libraries](#libraries)
2. [File Descriptions](#files)
3. [Content](#contents)

## Libraries <a name="libraries"></a>

    Pandas
    Numpy
    Matplotlib
    Seaborn
    Pickle
    NLTK
    scikit-learn
    

## File descriptions <a name="files"></a>

This repository contains the following files:
* **Recommendations_with_IBM.ipynb:** Jupyter notebook containing main implementation and analysis.
* **Recommendations_with_IBM.html:** A copy of Recommendations_with_IBM.ipynb in html format.
* **data/user-item-interactions.csv:** CSV file with user-item interactions.
* **data/articles_community.csv:** CSV file with indexed items.


## Contents <a name="contents"></a>

The project is organized along the following steps:

### I. Exploratory Data Analysis
Before making recommendations of any kind, you will need to explore the data you are working with for the project.

### II. Rank Based Recommendations
Find the most popular articles simply based on the most interactions. 
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular.

### III. User-User Based Collaborative Filtering
Look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users.

### IV. Content Based Recommendations
Given the amount of content available for each article, 
there are a number of different ways in which someone might choose to implement a content based recommendations system. 
For example, I chose to use my NLP skill to make Content Based Recommendations.

### V. Matrix Factorization
Finally, I complete a machine learning approach to building recommendations. 
Using the user-item interactions, I build out a matrix decomposition. Using the decomposition, 
I get an idea of how well I can predict new articles an individual might interact with. I discuss which methods I might use moving forward, 
and how I might test how well my recommendations are working for engaging users.
