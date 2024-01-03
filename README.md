# Read-from-CSV

## AIM:

## ALGORITHM:
## Step 1:
Import pands module as pd.
## Step 2:
Read a csv file name cars.csv.
## Step 3:
Print the first five rows and last five rows.
## Step 4:
Print the length of the rows and columns.
## Step 5:
End the program.
## PROGRAM:
# Program to read a csv file.
# Developed by:Naveen kumar v
# Reference number: 212223230140
import pandas as pd
df = pd.read_csv("cars.csv")
print(df.head())
print(df.tail())
print("Rows", len(df.axes[0]))
print("Columns", len(df.axes[1]))

## OUTPUT:
![image](https://github.com/Naveenkumarvedarajan/Read-from-CSV/assets/147140428/c05bf44c-160b-48b4-ae4f-5053ec95cf5f)
csv File:

![image](https://github.com/Naveenkumarvedarajan/Read-from-CSV/assets/147140428/6dc44e74-5cf7-4448-a76c-1e94dc33fc01)


## RESULT:
Thus the program is written to read a csv file.
