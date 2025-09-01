# -Yulu---Hypothesis-Testing

🚲 Yulu Electric Cycle Demand Analysis

📌 Project Overview

Yulu is India’s leading micro-mobility service provider, offering sustainable electric cycle solutions for daily commuting. Recently, Yulu has faced a dip in revenues and contracted a consulting company to understand the factors influencing the demand for shared electric cycles.

This project focuses on analyzing the Yulu dataset (yulu_data.csv) to identify the significant variables affecting demand, evaluate their relationships, and perform statistical hypothesis testing to derive insights.

🎯 Objectives

Identify significant variables in predicting the demand for shared electric cycles.

Understand how well these variables explain variations in demand.

Perform hypothesis testing to validate the relationships between demand and key factors.

📂 Dataset Description


Column	Description
datetime	Date and time of observation
season	1: Spring, 2: Summer, 3: Fall, 4: Winter
holiday	1 if the day is a holiday, 0 otherwise
workingday	1 if it is a working day (not weekend/holiday), else 0
weather	1: Clear/Partly Cloudy
2: Mist/Cloudy
3: Light Snow/Light Rain
4: Heavy Rain/Snow/Fog
temp	Temperature in Celsius
atemp	Feels-like temperature in Celsius
humidity	Humidity (%)
windspeed	Wind speed
casual	Count of casual users
registered	Count of registered users
count	Total rental bikes (casual + registered)
🔍 Methodology
1. Exploratory Data Analysis (EDA)

Data inspection: structure, missing values, summary statistics

Univariate analysis: histograms, boxplots, barplots

Bivariate analysis: scatterplots, heatmaps, group comparisons

2. Hypothesis Testing

2-Sample T-Test

Test whether working days affect the number of cycles rented

H0: No difference in rentals between working and non-working days

H1: Rentals differ between working and non-working days

ANOVA (Analysis of Variance)

Compare rentals across seasons

Compare rentals across different weather conditions

Chi-Square Test of Independence

Test if weather is dependent on season

3. Statistical Assumptions

Normality check (Histogram, Q-Q Plot, Shapiro-Wilk Test)

Homogeneity of variance check (Levene’s Test)

Proceed with tests and report assumptions validity
