# Water-Quality-Prediction-using-Decision-Tree-and-Random-Forest
This repository contains an analysis and prediction of water potability using Decision Tree and Random Forest classifiers. The objective is to predict whether water is potable (safe to drink) based on various features of water quality.

#Dataset Overview
The dataset includes the following features:
ph: pH value of water
Hardness: Hardness of water
Solids: Total dissolved solids in ppm
Chloramines: Chloramines in ppm
Sulfate: Sulfate content in mg/L
Conductivity: Electrical conductivity of water in μS/cm
Organic_carbon: Organic carbon content in ppm
Trihalomethanes: Trihalomethanes in μg/L
Turbidity: Turbidity in NTU
Potability: Whether the water is potable (0: Not Potable, 1: Potable)

#Key Steps in the Analysis
Data Loading and Overview: Load the dataset using Pandas and display basic statistics, including data types and missing values.
Data Preprocessing:
Fill missing values in 'ph', 'Sulfate', and 'Trihalomethanes' columns with their respective mean values.
Visualize the correlation between features using a heatmap.
Plot feature distributions and box plots to understand the data better.
Exploratory Data Analysis (EDA):
Display histograms for the distributions of numerical features.
Plot count of potable vs non-potable water samples.
Use pair plots to visualize relationships between features, colored by potability.
Modeling:
Decision Tree: Train a Decision Tree classifier and evaluate its performance using classification report and confusion matrix.
Random Forest: Train a Random Forest classifier and evaluate its performance using similar metrics. Also, determine feature importance.
Model Evaluation: Present confusion matrices visually to compare the performance of the classifiers.
Feature Importance: Visualize the importance of each feature as determined by the Random Forest model.

#Requirements
To run this analysis, you will need the following Python libraries:
numpy
pandas
matplotlib
seaborn
scikit-learn
