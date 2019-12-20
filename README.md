# Sparkify Project from Data Scientist Nanodegree

## Introduction

This is a project provided by Udacity and the goal of this project is to build a model 
that predicts the churn of a user based on variables such as gender and information about how the user uses the app. We will show the phases 
of the project.


## Loading and cleaning the dataset 

We load and clean the dataset, checking for invalid or missing data; for example, records without userids or sessionids.

## Exploratory data analysis 

We defined the variable churn and after that we do some exploratory analysis in order to find good predictors. 


## Modelling 

We split the full dataset into train, test, and validation sets. We tested out a random forest model with default values. Moreover, we evaluated the f1 metric, we do not use tuning parameters because it turns out to be computational expensive. Finally, the model works well in a small dataset, but this does not mean that work well in the full dataset. 











