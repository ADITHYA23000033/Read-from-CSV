# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.
## ALGORITHM:
## Step 1:
Import panda module as pd

## Step 2:
Read the csv file

## Step 3:
Print the first 10rows

## Step 4:
Print the next 5rows

## Step 5:
Print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: Aditya V
#Reg No: 23000033
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
```
## OUTPUT:
![6](https://github.com/ADITHYA23000033/Read-from-CSV/assets/148514544/de192fe2-4426-4cac-892c-7028596283cc)
## RESULT:
The program is executed successfully.
