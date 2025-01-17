# Exp-02-RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the given matrix and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: P.LOKNAATH
#RegisterNumber: 212223240080

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(a)
print(rank)
~~~
## Output:
![image](https://github.com/Loknaath-sec/RANK-OF-A-MATRIX/assets/145742558/0d7cf51d-eb35-4e19-9cd7-64e83d7d2658)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
