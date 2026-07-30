# Heart Disease Prediction

## Overview
Built a classification pipeline to predict the presence of heart disease 
in patients, as part of my Data Science & AI capstone project, comparing 
Decision Tree and Logistic Regression models.

## Dataset
UCI Heart Disease dataset (heart.csv) — 303 patient records with 14 
features including age, sex, chest pain type, cholesterol, resting ECG 
results, and maximum heart rate achieved.

## Approach
- Data cleaning: checked for nulls, removed duplicate records
- Exploratory Data Analysis: outlier detection via boxplots, correlation 
  heatmap across features
- Decision Tree Classifier — tuned `max_depth` (tested 1 through 15) to 
  find the best-generalizing depth
- Logistic Regression as a comparison model
- Evaluated using accuracy score and confusion matrix

## Results
- Decision Tree (max_depth=3): 87.9% accuracy
- Logistic Regression: 90.1% accuracy (best-performing model)
- Confusion matrix (Decision Tree): 34 true negatives, 46 true positives, 
  8 false positives, 3 false negatives

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Note
This was completed as an instructor-guided capstone project during my 
Data Science & AI program (Intellipaat, in collaboration with IIT Roorkee).
