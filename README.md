# Predicting-Medals-Machine-Learning

This repository contains a machine learning project focused on predicting medal outcomes in the Olympics. Using data, I cleaned and analysed the dataset to understand key factors that influence medal-winning performances. Then, I used machine learning models to predict the likelihood of winning a medal based on these factors.

To ensure the dataset was ready for analysis and modeling, I undertook several data cleaning steps, including:

Normalising Numerical Values: Numeric features were normalised to ensure they had a consistent scale.

Removing Zero Values: I identified and removed records with zero values in fields where zero would not be a logically valid entry (e.g., zero scores in events where performance metrics should be positive).

Addressing Infinite Values: Infinite values, which can occur due to calculation errors or division by zero, were replaced with NaN and handled appropriately to avoid computational issues.
