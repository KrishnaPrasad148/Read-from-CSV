# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.


## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by : Krishna Prasad.S
#Register Number: 212223230108
```
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:

![image](https://github.com/KrishnaPrasad148/Read-from-CSV/assets/147332763/112776e0-b32e-4457-aaed-9b2bb1003975)

![329157586-79637654-8062-4049-9ea8-4518f5b9fec6](https://github.com/KrishnaPrasad148/Read-from-CSV/assets/147332763/a624c2e7-e942-4430-a65c-f59e8997a36c)


## RESULT:
Thus the program is written to read the csv file.
