# Data-imputation-methods
Proof of sophisticated data imputation techniques like simple and multiple imputation using regression impact on the analysis data utility
The code uses Titanics Data set from Kaggle. 
The primary analysis is training the model to predict based of characteristics of the passanger if they survived or not
The original dataset has missing values. 
Two different imputation methods were used
1. The first imputation method was replacement with average mean age of the passanger class
2. The second imputation method was using linear regression to predict the missing age based on the known characteristics of the passanger 


This analysis is based on the paper published by A. Rogier T. Dondersa,b,c, Geert J.M.G. van der Heijdenc, Theo Stijnend, Karel G.M. Moons named "Review: A gentle introduction to imputation of missing values
" in the journal "Journal of Clinical Epidemiology" in the year 2006


The outcome is that method 2 performs better than method 1. 
