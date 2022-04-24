# CSE523-Machine-Learning-2022-Discover-Decipher
CO2 Emissions Prediction using Machine Learning Algorithms
# Introduction
The project and the presentation is showcased on the basis of the information available on kaggle.The usage of different techniques for the prediction of Co2 emissions  considering 11 features and respective vehicles(different models) was taken into consideration while implementation of the project. Regression  and classification machine learning algorithms were widely used in the project.
 
# Methods
    1.  Machine Learning 
    2.  Data Cleaning
    3.  Data analysis
# Technologies 
    1. Python
    2. Pandas, NumPy
    3. Scikit-learn
    3. Matplotlib
    4. Seaborn


# Implementation of Machine Learning Algorithms
 
# Regression analysis
 
    1. Linear Regression
    2. Polynomial Regression
    3. Decision tree regression 
    4. Random forest regression
 
# Classification analysis
 
    1. KNN classification
    2. Decision Tree  classification
    3. Random Forest classification
 
# Metrics/ Accuracy scores for Regression based algorithms
 
     1. Root Mean Square Error

     RMSE is used as one of factors to check on the quality of predictions by calculating the residuals which is a difference between the predicted and actual value    for each data point and thus by computing the mean of residuals with the square root measures the RMSE.

     2. Mean Absolute Error

     The most used metric for model evaluation specifically for regression models  , considering the test set there is a mean of absolute error for individual prediction errors on overall instances in a test set , prediction error depicts the difference between the actual and predicted value.

     3. R2 Score

     The R2 is considered as a coefficient of determination, It measures the amount of variance in predictions.
 
# Metrics for Classification based algorithms
      1. Confusion matrix

      The table/matrix depicts and visualizes the performance of the classification algorithm , the values described in matrix TP , TN , FP , FN play a vital role while visualizing the results.
      TP  : True positive (defines number of positives)
      TN : True Negative (defines number of negatives)
      FP  : False Positive(defines number of actual negatives classified as positives)
      FN : False Negative(defines number of actual positives classified as negatives)
      The accuracy calculated on the basis of these variables in the matrix  is (TP + TN) / (TP + TN + FP + FN)

 
2. AUC-ROC (Area under the curve and Receiver Operating characteristics )

      Visualizes and defines the quality of the performance for classification problems.
      ROC represents the probability curve and AUC defines the measure at which there is a separability.
      few measures taken into considertion are , 
      
         1. TPR(True Positive Rate) : (TP)/(TP + FN)
         2. FPR (False Postive Rate) : (FP)/(FP +TN)
