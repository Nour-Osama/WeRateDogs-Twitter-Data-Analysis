>This project was completed as part of Udacity's Data Analyst Nanodegree.

## Project Motivation

wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

## Brief Description

[WeRateDogs](https://twitter.com/dog_rates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) is a Twitter account that posts and rates pictures of dogs. These ratings often are not serious and have numerators that are greater than the denominators. Most of the necessary Twitter data has been provided by Udacity and includes information on each post, as well as details on each dog such as the name, rating, and stage (whether the dog is a doggo, floofer, pupper, or puppo). See below for definitions on the dog stages. However, not all of the desired data is present in Udacity's dataset, so I also use the Twitter API to gather additional data, as well as the an image classification data.

![Pasted image 20230724184800](https://github.com/Nour-Osama/WeRateDogs-Twitter-Data-Analysis/assets/69211641/d6deea9a-c691-4ff1-a6a3-e7528acb61df)


## Data Wrangling

In this project their are three kinds of datasets 
1.  Twitter archived dataset with some information about tweets
2. Tweets themselves on twitter
3. Dog breed classified images dataset 

So the initial goal is to gather all this data, assess them and clean them so that they can be used for analysis. That is the first portion of the project and all findings are seperately covered in the wrangle report.


## Data Analysis 

The cleaned datasets are then combined for analysis via key visualisations and derived values to gain further insights and correlations in the data. All findings are presented in the Analysis and Insights pdf.


## Requirements

-   Jupyter Notebook
-   Pandas
-   Numpy
-   Requests
-   Tweepy
-   json
-   Matplotlib
-   Twitter API
