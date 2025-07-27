# Flavors of Cacao - Chocolate Quality Analysis and Prediction

This project analyzes the **"Flavors of Cacao"** dataset, which contains expert ratings for over 1,700 dark chocolate bars. The goal is to identify the key factors that influence a chocolate's quality and build a model capable of predicting its rating.

## Objective

- Explore what characteristics affect chocolate quality.
- Predict the rating of a chocolate bar based on features like cocoa percentage, bean type, company location, and origin.

## Data Processing

- Text cleaning, normalization, and outlier handling.
- Clustering of categorical variables (grouped by regions).
- Missing value imputation using most frequent values.

## Exploratory Data Analysis (EDA)

- ANOVA and Pearson correlation to identify important features.
- Statistical tests and visualizations to uncover key relationships.

## Modeling

- Evaluated models: Linear Regression, Random Forest, XGBoost.
- Best performer: **Ensemble model** (average of LR + RF + XGB).
- Key metric: **R² = 0.2559**

## Conclusions

- Cocoa percentage, region, and bean type are key predictors of quality.
- The ensemble model offers a reasonable prediction performance.
- Areas for improvement: better prediction of extreme rating values.

## Data Source

- Original dataset available on Kaggle: [Flavors of Cacao](https://www.kaggle.com/datasets/rtatman/chocolate-bar-ratings)

---

Project by:  
**Asier Novio Cara** & **Martí Vallhonrat Rafart**  

