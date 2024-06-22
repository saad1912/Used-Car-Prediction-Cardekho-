# Used-Car-Prediction-Cardekho-

## Life cycle of Machine learning Project

### Understanding the Problem Statement
    *This dataset comprises data on used cars and their respective features, which are sold on cardehko.com in India.
    *The purpose is to build a model where user can predict the price of the car based on input features.
    
### Collecting Data
    *Given data is collected from cardekho.com through web scraping
    *Data used in this project is taken from Kaggle website
### Exploratory Data Analysis
    *Extracted Numerical and Categorical features, performed Univariate and Multivariate Analysis.
    *Further extracted Continuous and Discrete features from Numerical features, and plotted their relation with target variable.
### Data Cleaning
    *Handled Null values and Duplicates.
### Data Pre-Processing
    *Removed redundant columns
    *Multicollinearity check using Variance Inflation Factor
    *Capped Outliers using Boxplot formula for upper limit and lower limit
### Model Training
    *Encoded and Standardized Categorical and Numerical features.
    *Trained the model on 9 regression models, namely, Linear Regression,Lasso,Ridge,K-Neighbours Regressor,Decision Tree,Random Forest Regressor,
     XGBRegressor, CatBoosting Regressor, AdaBoost Regressor.
### Choosing optimal model
    *Performed Hyperparameter Tuning on the 4 best models based on R^2 score, namely, CatBoosting Regressor, XGBRegressor,Random Forest Regressor,K-Neighbours Regressor.
    *Final best model : CatBoosting Regressor with R^2 score of 0.9427.
    *Save the best trained model as a pickle file.
