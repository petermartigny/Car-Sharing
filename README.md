# Car Sharing Analysis

The dataset used here contains car sharing offers from drivers, during several months of service.
The goals of this project is to understand what will affect whether an offer will lead to a success (someone will share the ride) or a failure (no one shares the ride).

We preccess as follows: 

## Processing and cleaning
- Clean suspicious data
- Create business variables
- Create spatial features with reverse geocoder
- Make dumb analysis of the effect of each variable on the probability of success

## Classification pipeline
- Make the dataset balanced (so as to have the same number of positive and negative examples)
- Run classification algorithms (naive bayes or first logistic regression, then random forest and boosting methods).

## Guidelines for price recommendation
Use coefficients from logistic regression to lower the price when the probability of failure is too high
