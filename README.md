##Read-from-CSV
##AIM:

To read a csv file and access the data
##ALGORITHM:
Step 1:

Start python for doing the reading from CSV.
Step 2:

Import the required csv file.
Step 3:

Import pandas
Step 4:

Read the csv file by using df.read.
Step 5:

Display the Columns.
Step 6:

Display the Rows.
Step 7:

End the program
PROGRAM:
```
#Developed by :m.d.harini
#Reference Number : 22001980
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```
OUTPUT:-
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202022-10-11%2013-28-45.png![image](https://user-images.githubusercontent.com/113497680/195034023-e189bd2c-767e-4517-b40a-f192d5c7847f.png)

RESULT:

Therefore the program is successfully executed to read csv file and access the data in it.
