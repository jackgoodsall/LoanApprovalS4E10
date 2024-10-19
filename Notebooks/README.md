# Notebook overview

The notebooks go in the following order 

## EDA - Exploring the data

This note book goes through the process of EDA as below
* Checking missing values
* Visulising missing values (if appropiate)
* Visulsing numerical features dependence
* Visulising numerical features distribution
* Visuling cat features dependence/ distrubtuions

## Feature engineering

This note book goes through the process of feature engineering
* Dealing with missing values (if appropriate)
* Preprocessing data - Scaling data (if appropiate) and encoding
* feature engineering - creating new features

## Model building

This process goes through the process of model building including 

* Model selection
* Feature Importance
* Model tuning

## Submissions
Submission to kaggle competition will be shown below, public scores are the auc roc on a sub set of the submitted data.

## Submission 1 - XGboostClassifer
* Public score - 0.93248 
Can definately do better then that.

## Submission 2 - XboostClassifier 
Added more hyperparmaters to optuna search
* Public score - 0.94227

## Submission 3/4 
Adjusted hyperparamater searches 
Wasnt better then 2 

## Submission 5 
Added "risk flag" feature 
being cb on record and loan grade C or D.
* Public score - 0.94636

## Submission 6
Used cat boost
* public score - 0.95697

## Submission 7
Added loan utilisation, and extend risk factor to also grade E loans.
* public score - 0.95833