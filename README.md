# Read-from-CSV

## AIM:
To write a python program for reading the csv file content
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
~~~
To write a python program for reading content from a CSV file.
Developed by: GANESH G.
Register Number: 212223230059
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
~~~
## OUTPUT:
![image](https://github.com/ganesh10082006/Read-from-CSV/assets/151981672/af8fed8b-46b9-499d-be81-9fa6e5427a38)

![image](https://github.com/ganesh10082006/Read-from-CSV/assets/151981672/2a762172-8dde-4d83-a62c-796a7af83a93)

## RESULT:
Thus the program is written to read the csv file.
