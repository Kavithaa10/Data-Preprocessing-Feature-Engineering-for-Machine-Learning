# Data-Preprocessing-Feature-Engineering-for-Machine-Learning

### Data Import

#### import pandas as pd

#### import matplotlib.pyplot as plt

#### import numpy as np

#### import seaborn as sns

#### import warnings

### warnings.filterwarnings("ignore")

#### 1.	Import the housing dataset (housing.csv) and inspect!

### Features:

#### •	longitude: geographic coordinate (district´s east-west position)

#### •	latitude: geographic coordinate (district´s north-south position)

#### •	housing_median_age: median age of houses in district

#### •	total_rooms Sum of all rooms in district

#### •	total_bedrooms Sum of all bedrooms in district

#### •	population: total population in district
#### •	households: total households in district
#### •	median_income: median household income in district
#### •	median_house_value: median house value in district
#### •	ocean_proximity: District´s proximity to the ocean

### Data Cleaning and Creating Additional Features

#### 2.	Drop all rows with (at least one) missing value(s).
#### 3.	Add the additional Feature "rooms_per_household" (should be self-explanatory)
#### 4.	Add the additional Feature "population_per_household" (should be self-explanatory)
#### 5.	Add the additional Feature "bedrooms_per_household" (should be self-explanatory)

### Which Factors influence House Prices?

#### 6.	Calculate the Correlation between "median_house_value" and all features. Which factors seems to influence house prices/values?
#### 7.	Create a Seaborn Regression plot (jointplot) with income on the x-axis and house value on the y-axis.
#### 8.	Create the following scatterplot (df.plot(kind = "scatter")) with
#### •	longitude on x-axis
#### •	latitude on y-axis
#### •	size (s) of data points determined by population
#### •	color (c) of data points determined by median_house_value
#### •	Does this look familiar to you? It´s California. Let´s add the map of California saved in california.png.
#### •	Does this look familiar to you? It´s California. Let´s add the map of California saved in california.png.
#### •	Does this look familiar to you? It´s California. Let´s add the map of California saved in california.png.

### Advanced Explanatory Data Analyis with Seaborn

#### 9.	Add the additional column "income_cat" with the following income categories:
#### •	lowest 25% -> "Low"
#### •	25th to 50th percentile -> "Below_Average"
#### •	50th to 75th percentile -> "Above_Average"
#### •	75th to 95th percentile -> "High"
#### •	Above 95th percentile -> "Very High"

### Machine Learning - Predicting House Values

#### Based on the Explanatory Data Analysis,
#### •	select an appropriate ML Model (e.g. Linear Regression or RandomForest Regression)
#### •	split into Train and Test Set
#### •	prepare/engineer Features
#### •	Fit the Model (Train Set)
#### •	Test the Model (Test Set)
