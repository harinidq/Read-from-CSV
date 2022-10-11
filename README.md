# Read-from-CSV

## AIM:
  To write a python program for reading the csv file content.

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
## Developed by:m.d.harini
## REGISTER NUMBER: 22001980

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))

```

## OUTPUT:

![image](https://user-images.githubusercontent.com/113497680/195042066-cd80ccc7-1fee-444f-b720-b17dfdcc471f.png)



## RESULT:

Thus the program is written to read the csv file.
