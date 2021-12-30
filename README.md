# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define a function.

2.Get the values from the user.

3.Compare the values o find the LU decomposition of the matrix.

4.Use for() and if() loop to find the LU Decompostion. 
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:R.Hemapriya 
RegisterNumber:21004884
import numpy as np
import scipy
from scipy.linalg import lu
A =eval(input())
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:R.Hemapriya 
RegisterNumber:21004884
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv= lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)

*/
```

## Output:
![lu decomposition](https://github.com/Hemapriya-2004/LU-Decomposition/blob/79ca1cd1f0c2e51d6fd3ff7065bd13796aac9343/ss1.PNG)
![lu decomposition](https://github.com/Hemapriya-2004/LU-Decomposition/blob/79ca1cd1f0c2e51d6fd3ff7065bd13796aac9343/ss.PNG)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

