# Rental Price Prediction

Short-stay rental price prediction using linear regression in R. Built as a DataCamp Professional Data Scientist certification case study for Inn the Neighborhood, a fictional property rental platform.

## Goal

Predict nightly rental prices within a 25 dollar margin of error to help property owners estimate their potential earnings.

## Dataset

8,111 rental property listings with the following features: location (latitude, longitude), property type, room type, number of bathrooms and bedrooms, and minimum nights required.

## Workflow

* Exploratory data analysis and outlier removal
* Feature engineering (log transformations on price and minimum nights)
* Linear regression with 5-fold cross-validation using the caret package

## Results

The best model achieved an MAE of \~62 dollars and RMSE of \~111 dollars, falling short of the 25 dollar target. The summary discusses potential improvements such as adding neighborhood data, spatial features, and more complex models like random forest or gradient boosting.

## Files

* notebook.ipynb: Full analysis and modeling workflow
* presentation.pdf: Non-technical summary for stakeholders

## Requirements

R 4.4.0 with the following packages: tidyverse, caret, rsample, gridExtra, repr

