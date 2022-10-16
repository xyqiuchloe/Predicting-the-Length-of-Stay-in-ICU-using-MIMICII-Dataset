# Predicting-the-Length-of-Stay-in-ICU-using-MIMICII-Dataset
Machine Learning Project using Python and SQL in python

## Project Overview

#### Background and Aim. 
Long stays in the Intensive Care Units (ICUs) are an economic burden to individuals and the economy as a whole. The main goal of hospitals is to decrease the length of stay(LOS). In this study, we identify key risk factors of ICU stay with four different models.

#### Materials and Method. 
12 explanatory variables (clinical and demographic) and 2 outcome variables (length stay and length of stay group) of 2,234 patient records were used to build Elastic Net regression model, Regression Tree model, Random Forest regression, and Artificial Neural Network (ANN) models. 

#### Results. 
The test MSE of the elastic net regression model is 52.0; the regression tree model had a test MSE = 53.4; the random forest regression had a test MSE = 59.7; the ANN model for regression had a test MSE = 57.93 and the ANN model for classification had a model accuracy = 76.6%. Based on the models, we identified the important factors related with prediction of LOS as: SAPS II, age, gender, religion, marital status, weight, admission source, care unit. 

#### Conclusion. 
Our models indicate that SAPS II is associated with longer LOS, and weight, admission age, and ICU stay care unit being MICU is associated with shorter LOS.

