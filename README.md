# Airbnb_NY_analysis

This project focuses on model optimization process of predicting the outcome variable and comparing model accuracy on prediction.  
Used RStudio for analysis, a dataset file “AB_NYC_2019.csv” (Dgomonov, 2019) containing 48,895 observations of 16 variables was imported into a data frame by calling the read.csv() method.  

Data cleaning and profiling were performed on the dataset. 

Correlation matrix was generated which indicated where any multi multicolinearity between variables existed or not.  We have performed machine learning algorithsm such as full linear regression, stepwise regression, regression tree and gradient boosting.The prediction accuracy of new models built using optimization techniques will be compared with the benchmark model.  Log transformation and interaction terms have been utilized for model optimization. XGBoost, a specific implementation of Gradient Boosting, was utilized more accurate approximations to find the best tree model.  XGBoost only takes numeric data matrix so all data used were converted into numeric formats.  When making predictions using this tree model, a much lower MAPE of 5.85% and RMSE of 15.02.  
