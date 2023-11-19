# Medical Insurance Cost Estimator

Health Insurance is medical coverage that helps you meet your medical expenses by offering financial assistance. Due to the high cost of hospitalization expenses, it is important to have a health insurance plan in place. In the current pandemic situation, health insurance plays a vital role in safeguarding your finances.

## Problem Statement & Objective
 

Imagine yourself working as a data scientist in an insurance company. Your manager asked you to come up with a data science solution to estimate the medical cost of an individual who has bought health insurance in the institution. Build a machine learning model to estimate the medical cost of an individual.

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, xgboost, lightgbm  
**Data Source:** Zach Stednick 
**Data Link:** https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv

## Data Dictionary
<b>age</b>: age of primary beneficiary. (if the age is given in decimal, consider it as the nearest integer, for example, if age = 19.1, it's nearest integer is 19, if age = 22.6, it's nearest integer is 23)

<b>sex</b>: insurance contractor gender, female, male

<b>bmi</b>: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

<b>children</b>: Number of children covered by health insurance / Number of dependents

<b>smoker</b>: Smoking

<b>region</b>: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

<b>charges</b>: Individual medical costs billed by health insurance

## EDA
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights.

Dataset Shape: (3630, 7) 
|   | Name     | dtypes  | Missing | Uniques |
|---|----------|---------|---------|---------|
| 0 | age      | float64 | 0       | 1589    |
| 1 | sex      | object  | 0       | 2       |
| 2 | bmi      | float64 | 0       | 2322    |
| 3 | smoker   | object  | 0       | 2       |
| 4 | region   | object  | 0       | 4       |
| 5 | children | int64   | 0       | 6       |
| 6 | charges  | float64 | 0       | 2951    |


