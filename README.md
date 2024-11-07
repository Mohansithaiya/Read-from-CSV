# DATE: 
# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Import linear model from sklearn.
### Step 3:
Declare weight and volume in x.
### Step 4:
Declare CO2 in y.
### Step 5:
Using regression formula print the result.

## PROGRAM:
```
# Developed By: MOHAN S
# Register Number: 212223240094

import pandas as pd
from sklearn import linear_model
data=pd.read_csv('car.csv')
x=data[['Weight','Volume']]
y=data['CO2']
regression=linear_model.LinearRegression()
regression.fit(x,y)
print("Coefficient:",regression.coef_)
print("Intercept:",regression.intercept_)
predictCO2=regression.predict([[3300,1300]])
print("CO2 required is",predictCO2)
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/483aee8c-70ce-409b-a845-aff104c1339e)

## RESULT:
Thus the program is written to read the csv file.
