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
RegisterNumber: 22005014
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
RegisterNumber: 22005014
*/
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
![bb](https://github.com/manojMKJ/LU-Decomposition/assets/120717614/f8575d6a-ba49-4af5-9096-9736c3316f49)
![image](https://github.com/manojMKJ/LU-Decomposition/assets/120717614/64862e73-8e84-470b-80b0-283eba89429c)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

