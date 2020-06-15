# Machine-Hack---Ecommerce-Price-Prediction

This is an ongoing hackthon available on Machine-Hack, The aim here is to predict the prices of items available on ecommerce websites. 
The data contains 3 files (Train.csv, Test.csv, Sample_Submission.csv). The evalution criteria is RMSLE. I am builiding a deep regression model by stacking over 9 models and blending the predictions from each model.

Since this is a Regression type problem, I will be making the final model based on the following models :
1. Deep Neural Network (Cause Neural Networks are love :p)
2. Xgboost
3. Catboost
4. SVR (Support Vector Regressor)
5. Ridge Regressor
6. Light gbm Regressor
7. Random forest based regressor
8. Gradient boosted regressor
9. Stackgen model


The competition started on Saturday and so far I have created a baseline model which is able to achieve a score of 0.811.
The aim is to get a score of 0.5 or less
I will be doing some feature engineering as well which will improve the score.
The idea behind blending the predictions is to minimise the overfitting caused by individual models.
The weights for each model can be assigned via hit and trial or by fitting a neural network.
I will upload the code in a few days when I am able to achieve the target score.
