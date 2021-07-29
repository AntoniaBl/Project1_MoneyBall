## Ironhack Data Analytics Bootcamp 
# **Project 1 FIFA MoneyBall**

## **Goal of the project**

This project is part of the Ironhack Data Analytics Bootcamp. The main objective of this first project is to analyse 3 chosen questions on the provided FIFA data set by applying data cleaning techniques, statistiscal methods and visualization.
In addition, machine learning techniques are used to predict the market value of players.

Objectives: 
1. 
2.
3.

---
## Content
- [Exploring Data] (#Exploring Data)
- 
- 
---


## **Exploring the Data**
The FIFA data (fifa21_male2.csv) was retrieved from Kaggle: https://www.kaggle.com/ekrembayar/fifa-21-complete-player-dataset). 
The initial dataset contains 17125 rows and 106 columns including player information(name, age, position, club, rating, market value) and skill-related information and scores(e.g. passing, defence, shooting, goal keeping and so on).

## **Data cleaning** 

The data cleaning process was done in the following steps:

1.  (removing redundant datas and handling null values)
2.
3.
4.
5.

The dataset rows and columns decrease to 17092 rows and 84 columns.

## **Libraries**

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import scipy.stats as stats
import os
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score, mean_squared_error, mean_absolute_error
import warnings

---

## **Results**
Objective 1:

Objective 2:

Objective 3:


### Machine learning: Predict market value




