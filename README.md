# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix

## ALGORITHM:
### Step 1:
Import Numpy module as np
### Step 2:
Create empty lists.
### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Print the inverse of the array using np.linalg.inv


## PROGRAM:
```
To write a python program to find the inverse of a matrix.
Developed by:  M.RAJESHKANNAN
Register Number: 21500434

import numpy as np
rows=int(input())
columns=int(input())
l1=[]
for i in range(rows):
    temp=[]
    for j in range(columns):
        t=int(input())
        temp+=[t]
    l1+=[temp]
print(l1)
print(np.linalg.inv(l1))
```

## OUTPUT:

![Screenshot 2022-02-11 232955](https://user-images.githubusercontent.com/93901857/153644650-608135be-a380-4494-9add-c3de0798319c.jpg)

## RESULT:

Thus a program is written to find the inverse of the matrix.


