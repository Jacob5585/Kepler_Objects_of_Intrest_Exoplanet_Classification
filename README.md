# Kepler_Objects_of_Intrest_Exoplanet_Classification

## CS542 Machine Learning Project

This project explores the Kepler K1 from NASA to test machine learning models in the task of classifying between exoplanet potential candidates and false positives  
This project covers:
1. Exploring the dataset
2. Cleaning the data
3. Data scaling
4. Selecting which features to train on
5. Splitting the data
6. Using validation
7. Then testing models

## Code
1. explore_data_project.ipynb Looks into the dataset and plots grpahs
2. data_cleaning_project.ipynb Cleans up Nah values in the dataset
3. feature_importance_project.ipynb Explains the most important features to use in model training and testing
4. models_project.ipynb Splits the data, setups KFOLD, trains 5 differnt models, then tests those 5 models

## Dataset
1. NASA_Exoplanet.csv Base dataset from NASA's kaggle repo
2. NASA_Exoplant_df_merged_meadian.csv Post cleaning data
3. NASA_Exoplanet_transit.csv Transit and Dipostion features selected for traning and testing