# Heart-Disease-Prediction

## Overview
This project created `two logistic regression models` to predict the likelihood of heart disease. And created a `classification random forest` to predict the risk of heart disease. We also created a regression random forest to predict maximum heart rate. The analysis compares model performance, evaluates statistical significance, and highlights practical applications for medical risk assessment and research. Created as a project for MAT 303 at Southern New Hampshire University.


## Dataset
The dataset used in this project is the [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease), which contains 303 patient records with various health indicators.


## Models / Methods
1. Logistic Regression
   *  Built two different models with different predictor sets
   *  Evaluated significance using Wald’s test and Hosmer–Lemeshow GOF  

2. Random Forests (Classification)
   * Used 85% training / 15% testing split
   * Optimized the number of trees based on classification error
   * Evaluated with confusion matrix, accuracy, precision, recall, and ROC/AUC

3. Random Forests (Regression)
   * Predicted maximum heart rate (continuous)
   * Evaluated using Root Mean Squared Error (RMSE)


## Technology used
1. R

2. Jupyter notebook


## Results 
Logistic regression models provided strong interpretability and accuracy, making them well-suited for understanding risk factors. Random forests captured non-linear relationships but tended to overfit the small dataset. Overall, the second logistic regression model achieved the best balance of accuracy, precision, and recall.


## Author 
Creston Getz

Southern New Hampshire University – MAT 303(Applied Statistics II for STEM)
