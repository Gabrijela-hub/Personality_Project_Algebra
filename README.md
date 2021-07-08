# Personality Project Algebra
Introduction course in Data Science project solution

## Data
Data for this project can be found at: https://drive.google.com/drive/folders/1otfejbiwkHbfou9v0DruVhYP2iJo-9R5?usp=sharing

Original data found at: https://www.kaggle.com/tunguz/big-five-personality-test

## Introduction

This data set contains answers on IPIP 50 personality inventory. 50 items measure 5 personality dimensions: Extraversion, Neuroticism, Agreeableness, Conscientiousness, and Openness.
Each dimension is described by 10 items (see in Codebook) and some need to be reverse coded in order to get a proper result for every dimension. The data set also contains time in milliseconds for every item, denoting how much time the person spent on every item.

## Data analyses

The code deals with some data cleaning and wrangling in order to make it suitable for three main components of data analysis.

Time spent per item in each dimension

The average time per item per dimension is displayed in a line chart. There is a trend of reduction in time needed for respondents to give answers as the inventory progresses.

Respondents’ result on each dimansion

The score on each personality dimension is calculated as a mean of sums on item answers for that dimension. Distribution for each dimension can be seen in a box and whisker plot. Correlations between the dimensions are visualized through a heat map.

Logistic regression

The goal was to predict if a respondent is in the top 5% on the neuroticism dimension using the remaining four personality dimensions. Neuroticism was chosen as high scores on this dimension can be recognized as a risk factor for psychopathology and has been shown to have a solid biological basis. The confusion matrix is presented through percentages on a heat map.

## Technologies

Python
Version 3.8.5


Libraries: 
Pandas
Numpy
Scikit Learn
Seaborn

## Launch
 
The code file can run in either Jupyter Notebook or Google Colaboratory. To access data, make a copy of the database on your device. 
