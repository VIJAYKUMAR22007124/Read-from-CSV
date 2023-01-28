# Read-from-CSV

## AIM:
To read from CSV.

## ALGORITHM:

### Step 1:
Import pandas package

### Step 2:
Open the csv file in read mode.

### Step 3:
Print head.

### Step 4:
Print tail.

### Step 5:
Print rows and columns.

## PROGRAM:
```Python
import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row: ', len(f.axes[0]))
print('Col: ', len(f.axes[1]))
```

## OUTPUT:
![image](./Screenshot%20from%202023-01-28%2014-41-36.png)

## RESULT:
Thus, the CSV is read.
