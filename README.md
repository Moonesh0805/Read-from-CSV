# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.
## ALGORITHM:

### Step 1:
Import panda module as pd
### Step 2:
Read the csv file
### Step 3:
Print the first 10rows
### Step 4:
Print the next 5rows
### Step 5:
Print the toal no.of rows and columns with argument 0 for row and argument 1 for column.
## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: MOONESH P
#Register Number: 23001144

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
![OUTPUT](/CSV.jpeg)
## RESULT:
The program is executed successfully.