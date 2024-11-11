# DATE: 
# EXP.NO.12 Read-from-CSV

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
# Python Program for reading the csv file content.
# Developed By: MOHAN S
# Register Number: 212223240094

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![alt text](output.png)

## RESULT:
Thus the program is written to read the csv file.
