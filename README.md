# Read-from-CSV

## AIM:
To write the program to read the csv file

## ALGORITHM:
### Step 1:
Load the csv into a DataFrame
### Step 2:
Print the number of content to be displayed using df.head()
### Step 3:
The number of rows returned is defined in Pandas option settings
### Step 4:
Check your system's maximum column with the pd.options.disply.max_column statement
### Step 5:
Increase the maximum number of rowa to display the entire DataFrame

## PROGRAM:
DEVELOPED BY : R Manojkarthik

REGISTER NUMBER : 22003728
```
import pandas as pd
df= pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/119560395/214846063-dd1caaf4-eb5f-4100-b021-8cab9e806948.png)

## RESULT:
Thus the program is written to read the csv file.
