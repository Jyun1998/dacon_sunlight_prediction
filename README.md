# Dacon sunlight prediction
Public 71/1477  Private 98/1477

## Topic 
Predicting solar power generation utilizing regional weather data and historical power generation data within given time zone

## Expected Effect
 Utilizing power consumption forecast data given time zone for efficient solar power generation and optimized supply plan

 ## Method
 ### EDA
 ### Modeling & Tuning
 Model selected : ExtraTreesRegressor, ElasticNet, RandomForestRegressor, Lasso
 Hypter-parameter tuning: hyperopt
 Ensembling : sklearn.ensemble.StackingRegressor with 5-fold and final modelling with RF