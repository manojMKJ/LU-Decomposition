# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. give the prepared matrix and assign in np.array()
3. Using np.linalg.matrix_inv(),we can find the LU Decomposition of a matrix
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Manoj kumar G
RegisterNumber: 212222230078
*/
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Manoj kumar G
RegisterNumber: 212222230078
*/
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:

<img width="1261" height="915" alt="MA ex5 (1)" src="https://github.com/user-attachments/assets/e01e13d4-eb04-4ba8-aa2d-9aa437b72dc1" />

<img width="1255" height="900" alt="MA ex5 (2)" src="https://github.com/user-attachments/assets/8ee4ef4c-dd3d-4ed6-a146-e81bb9efb617" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

