# Read-from-CSV

## AIM:
To read from csv file
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2: Read the CSV file using read_csv method.
### Step 3: Use head and tail method to get the required contents from the file.
### Step 4: Use len() method to get the number of rows and columns
### Step 5: Print the output.

## PROGRAM:
Developed by: T MOUNISH
Ref.no:23002806
```
import pandas as pd
f=pd.read_csv("/content/nba (2).csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:

![WhatsApp Image 2023-12-25 at 16 19 23_9190fbfd](https://github.com/MounishT/Read-from-CSV/assets/138955798/67f6ebe7-5c09-4748-a0de-0e9d2709cd35)

## RESULT:
Thus a python program is written to read the contents of a csv file
