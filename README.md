# Read-from-CSV

## AIM:

To write a python program to read contents from a CSV file.

## ALGORITHM: 
### Step 1:
Import sys
### Step 2: 
Initially make count = 0 
### Step 3: 
Open the content file using command line arguments.
### Step 4:  
By using for loop name the function as "line"
### Step 5: 
Split the line using .split
### Step 6: 
Split the line using .split

## PROGRAM:
~~~
#Program to read contents from a CSV file.
#Developed by: NAVEEN KUMAR.B
#Reg No: 212222230091

import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
~~~
## OUTPUT:

![6](https://github.com/ArchanaSharikalHarinarayanan/Read-from-CSV/assets/148514544/10fae76f-62ff-4d42-a174-bf5d3551f542)

## RESULT:

The program is executed successfully.
