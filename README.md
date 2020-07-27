# Project 2: Ames Housing Data and Kaggle Challenge

### Contents:
- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Data Sources](#Data-Sources)
- [Data Dictionary](#Data-Dictionary)
- [Conclusions/Recommendations](#Conclusions/Recommendations)

<a id=Problem Statement></a>
## Problem Statement

Whether they are real estate agents or homeowners, sellers in Ames, Iowa want to know just how much can they get for a house.  Houses come in many shapes and sizes and can be fitted with a myriad of different features,  all of which can play into a buyers final decision on how much they will pay.  Sellers want to know if they’re getting a good deal.  What should be the asking price?  Can I get more if I make home improvements?  

<a id=Executive Summary></a>
## Executive Summary

To estimate housing prices, a modeling regression was used too assess the predicted power of the most likely features and factors affecting the final sale price of houses in Ames, Iowa.  A multiple linear regression (MLR) was used to predict the sale price in a test dataset and then submitted to Kaggle to assess the model against unknown data.
The modeling process consisted of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)

<a id=Data Sources></a>
## Data Sources
[Test Data](data/test.csv)
[Train Data](data/train.csv)
[Sample Subreg](data/sample_sub_reg.csv)

<a id=Data Dictionary></a>
## Data Dictionary
The data dictionary is profuse.  It can be found here:
https://www.kaggle.com/c/dsir-420-project-2-regression-challenge/data

<a id=Conclusions/Recommendations></a>
## Conclusions/Recommendations

There are strong correlations between overall quality, year remodeled, and various features related to square footage.  It is recommended to make home improvements such that would enhance the overall quality and/or increase square footage.  

Such improvements may include:
- Kitchen remodel
- Additional living space or garage

Using linear regression, final accuracty scores for this model are 0.89 on the testing set and 0.92 on the training set.

