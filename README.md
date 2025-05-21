# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start
### Step 2: Import the NumPy library to perform matrix operations.
### Step 3: Define the matrix for which the inverse is to be calculated (as a NumPy array).
### Step 4: Calculate the determinant of the matrix using numpy.linalg.det().
### Step 5: Check if the determinant is not equal to zero:
If yes, proceed to compute the inverse using numpy.linalg.inv().
If no, display a message that the matrix is singular and does not have an inverse.
### Step 6: Display the result (inverse or error message).
### Step 7: End

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

