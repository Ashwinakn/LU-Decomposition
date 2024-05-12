# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and
   create the variable as 'X' include the package in that variable.
5. Print the variable 'X' 


## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: ASHWINA K N
RegisterNumber: 212223230025

import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: ASHWINA K N
RegisterNumber: 212223230025


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:

![math 5 1](https://github.com/Ashwinakn/LU-Decomposition/assets/152128332/b8adbab2-1413-483e-ae76-336edd936cd7)

![math 5 2](https://github.com/Ashwinakn/LU-Decomposition/assets/152128332/6f5c66d8-1609-4c93-bf56-44252d888f20)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

