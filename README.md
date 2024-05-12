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
#To write a python program for reading content from a CSV file.
#Developed by: Mahalakshmi R
#Register Number: 212223230116

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-05-12 132659](https://github.com/Mahalakshmi230/Read-from-CSV/assets/149365324/6e85ad7f-f34d-49c2-8ead-8a7eb5cd066e)
![Screenshot 2024-05-12 132728](https://github.com/Mahalakshmi230/Read-from-CSV/assets/149365324/e6ae35d6-4508-458a-b183-ceb10320d8f9)

## RESULT:
Thus the program is written to read the csv file.
