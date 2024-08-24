# california_housing_project2


## I) code explination

### 1) import libraries & loading the dataset
  -> import numpy, pandas, matplotlib.pyplot  
  -> get dataset from sklearn

### 2) understanding & preparing the dataset
   -> apply .keys() method to get a list of all the attributes for the dataset  
   -> create a dataframe from the given data  
   -> add a column for the output variable  
   -> apply, info(), isnull().sum(), describe() to get data for getting information related to the data for inference
   
### 3) EDA => corr, plotting
   -> apply corr() to get how releted one variable is to another  
   -> use scatter() & regplot() to get the visulization for the same
   
### 4) preprocessing data: independent & dependent features, train test split, standardize data, linear regression algo  
   -> sperate the data into dependent & independent features using iloc  
   -> train the model using train test split  
   -> create an object scaler from the class StandardScaler  
   -> fit_trasform the x training data & transform the x test data
   
### 5) checking performance & metrics  
   -> create a regression object from the class LinearRegression
   -> put the training data in this model  
   -> predict the y test value when x test data is given  
   -> get the coefficients & intercept  
   -> use scatter plot to check the relation between the actual y test data & the y predicted data  
   -> find the residuals to get the variation the actual vs predicted  

   -> import performance metrics like mean_absolute_error, mean_squared_error, r2_score & check performace  
   
### 6) adding new data points, pickling the model for deployment
