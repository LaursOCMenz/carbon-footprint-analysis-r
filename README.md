# 🌱 Household Carbon Footprint Analysis

## Overview

This project explores factors associated with household carbon
footprints and recycling behaviour using R.

The analysis involved data cleaning, exploratory data analysis,
data visualisation and statistical modelling.

## Research Questions

1. Which household characteristics are associated with carbon footprint?
2. Which factors are associated with the likelihood of regularly recycling?

## 🛠️ Tools & Technologies

- R
- tidyverse
- ggplot2
- mgcv
- car

## 📊 Methods

The analysis included:

- Data cleaning and quality assessment
- Exploratory data analysis (EDA)
- Data visualisation
- Spearman's correlation
- Generalised Additive Models (GAM)
- Multiple linear regression
- Logistic regression

## 📊 Project Visualisations

### Spearman Correlation Between Numerical Variables

Spearman's rank correlation was used to examine relationships between 
the numerical variables. Carbon footprint showed the strongest positive 
association with annual energy consumption (rₛ = 0.76), followed by 
income (rₛ = 0.52).



## 🔎 Key Findings

The final multiple regression model explained approximately 94%
of the variation in carbon footprint within the analysed sample.

Annual energy consumption and income were identified as important
predictors, with evidence of non-linear and interaction effects.

Recycling behaviour was investigated separately using logistic
regression.

## 📂 Data

The dataset used in this project was provided for academic purposes
and is therefore not included in this public repository.

The R Markdown and rendered HTML report are provided to demonstrate
the analytical workflow and results.

## 📁 Repository Contents

- `carbon-footprint-analysis.Rmd` — R Markdown containing the analysis and code
- `carbon-footprint-analysis.html` — Rendered report containing code, outputs and visualisations
- `README.md` — Project overview
