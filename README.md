# PumpItUp
Pump it up Machine Learning Group Project MBD16

# DrivenData-PumpItUp

This repository contains R code for the [Pump it Up: Data Mining the Water Table](http://www.drivendata.org/competitions/7/) competition on [Driven Data](http://www.drivendata.org).

The data is provided by [Taarifa](http://taarifa.org) and the [Tanzanian Ministry of Water](http://maji.go.tz). The goal is to predict whether a water pump is functional, functional but needs repairs or non functional.

Sign up at Driven Data to download the following files:

* `SubmissionFormat.csv`
* `Test set values.csv`
* `Training set labels.csv`
* `Training set values.csv`

## Read the data and do some preprocessing

The first step is to read the data and set some values to missing (`NA` in R).

## Engineer features

The next step is to clean up the features (transform some, remove others) and possibly engineer some new features.

## Predict status with a random forest

Use a random forest to predict the functionality status of pumps in the test set.
