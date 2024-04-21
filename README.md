# INVERSE-OF-A-MATRIX
## Aim:
## DATE: 09.03.2024
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Importing the NumPy library using the statement import numpy as np.
### Step 2: Define a 3x3 matrix A with the specified values.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of matrix A using the print() statement.
### Step 5: End the program.

## Program:
```
#write a program to find the solution to a system of linear equations [6,2,3],[3,1,1],[10,3,4]

#prgram to find the inverse of the matrix for the given matrix 
#devoleped by : poovarasu
#registerNumber:2305002017

import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
i=np.linalg.inv(a)
print("the inverse of the matrix a is\n",i)

```
## Output:
![3](https://github.com/Poovarasu8/INVERSE-OF-A-MATRIX/assets/155505954/1c0e594c-4695-4555-9919-8dc1f49793bc)

## Result:
Thus the inverse of given matrix is successfully solved using python program

