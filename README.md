# Read-from-CSV
## AIM:
To write a python program for getting the word count from the contents of a file using command
line arguments.
## EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7
## ALGORITHM:
### Step 1:
import sys module
### Step 2:
Using sys module,open a file with read mode
### Step 3:
Read the file and split the file and stor in the variable
### Step 4:
print the length of the variable
### Step 5:
End the program
## PROGRAM:
```
'''
write a program to read a csv file
Developed by : Vikaash K S
Reference no:23013426
'''
import pandas as pd
df=pd.read_csv("cars.csv")
print(df.head())
print(df.tail())
print("Rows",len(df.axes[0]))
print("Columns",len(df.axes[1]))
```
## OUTPUT:
![exp 6 op](https://github.com/Vikaash19/Read-from-CSV/assets/148514589/cfbe76f3-68ef-4e21-8e62-a35c6bd5dc66)
### CSV FILE:
![exp 6 csv](https://github.com/Vikaash19/Read-from-CSV/assets/148514589/c22f9f0d-485e-4442-baf6-8f7cfbfc12fd)
## RESULT:
Thus the program is written to read a csv file.
