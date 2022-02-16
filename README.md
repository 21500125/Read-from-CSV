# Read-from-CSV

## AIM:
To write a python program to read from csv

## ALGORITHM:
### Step 1:
load the csv into a data frame
### Step 2:
print the number of contents to be displayed using df.head()
### Step 3:
the number of rows returened is defined in pandas option settings
### Step 4:
check your systems maximum colum with the pd.options.display.max_colums statement
### Step 5:
increase the maximum number of rows to display the entire data frame
## PROGRAM:
```
'''
Developed by: Sithi hajara I 
RegisterNumber:21500125
'''
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("number of colum ",len(df.axes[0]))
print("number of rows),len(df.axes[1]))
## OUTPUT:
![sh](https://user-images.githubusercontent.com/94219582/153771226-4f89a283-20bb-4630-9ce3-07a8d07b1747.jpeg)
```
## RESULT:
Thus the python program runs successfully
