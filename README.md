# LinearRegression-HealthCosts
# Purpose:
Project for implementing linear regression to predict medical costs. Additionally, to become more familiar with linear regression and interpreting the model. 

# Methods:

Imported dataset from Kaggle on Health Costs based on BMI, Sex, Children, Region, Smoking, 

Created a pandas dataframe and dummy variables as necessary. 

Expored potential correlations to understand attributes that would impact linear regression the most. 

Created model with Sklearn linear regression. 

Experimented with removing certain attributes to assess model accuracy. 

# Results 

Used R^2 and Mean Absolute Error (MAE) to interpret the model performance. 
MAE: 4046.9883522195664
R^2: 0.7583790612051051

R^2 value appears to be a good fit but is relative the problem that we are looking to solve. That is why we additionally look at the 
In our case the mean health charges was $13,270 with a standard deviation $12,110 of and the MAE was $4,046. Given the large standard devation in the dataset the MAE is a reasonable error for a simple linear regression applied to this dataset.  

Coefficients: 
BMI - 354.87   
Age - 243.37
Smoking - 23469.73

Smoking vs non-smoking will increase costs by $23,469.73. With each increase in BMI unit there is a predicted increase of $354.87 and with increase of each year in age there is a predicted increase of $243.37

# Learnings: 

I expected BMI to have a bigger impact on health costs. Important to complete exporatory data analysis to confirm/deny presonal assumptions / bias. 
Understanding coeffiecients and error of the linear regression. 


