# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy to perform the inverse of matrix operation
### Step 2: Create the matrix to find the inverse,representing as a Numpy array
### Step 3: Use the numpy. linalg.det() function to ensure the determination of matrix is non-singular matrix have inverses 
### Step 4: End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: THARRUN D
#RegisterNumber:212224240170

import numpy as np

matrix = np.array([[1, 0, 3],
                   [-1, 2, -2],
                   [2, 3, -1]])
                   
inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)

```
## Output:

![Screenshot 2025-05-16 220016](https://github.com/user-attachments/assets/bcaf91ea-54ec-4e0b-b94c-dcfccbee9f7d)


## Result:
Thus the inverse of given matrix is successfully solved using python program.

