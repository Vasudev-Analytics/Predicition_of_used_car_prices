# Predicition_of_used_car_prices
Dataset is procured from Kaggle and the dataset has used car prices from Craigslist Website. It is an online advertising company in the U.S. Using regression analysis, XG Boost turned out to be the best model and prices are predicted. On this dataset, scaled and unscaled data results are also compared.
This dissertation aims to accurately predict used car prices using machine learning techniques. The motivation is the increased demand for used cars due to new car shortages and high prices. A dataset of used car listings from Craigslist is analyzed. After data cleaning and pre-processing, both a baseline model retaining all features and an optimized model with feature engineering are developed.

The optimized model groups the features 'manufacturer', 'state', and 'paint color' into new attributes representing maintenance costs, taxes, and depreciation. Five regression algorithms - linear regression, support vector regression, decision tree, random forest, and XGBoost - are tested on scaled and unscaled data for both models. The XGBoost model performs best overall, with an R-squared of 0.82 on scaled test data.

Key factors influencing price are identified as car age, odometer reading, cylinder count, manufacturer, and state. The models provide a good starting point to predict used car prices, though additional features could further improve accuracy. Deployment would require ongoing data collection and monitoring.

Concepts covered:

Data Analytics using CRISP-DM approach
Regression algorithms in machine learning
R programming language for data analytics; tidyverse, dplyr, caTools, ggplot2, skimr, and other various libraries explored
Predictive analytics for price forecasting
Commercial acumen applied with real-time web data
Scaled and unscaled data analysis and comparison attempted
