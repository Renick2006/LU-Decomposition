# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Renick Fabian Rajesh
RegisterNumber: 24900741
*/
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Renick Fabian Rajesh
RegisterNumber: 24900741 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
b=np.array([4, 5, 7])
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:
i] To find the L and U matrix
![image](https://github.com/user-attachments/assets/4d766e0c-ab81-44a0-9710-e7993b14bfc1)
ii] To find the LU Decomposition of a matrix
![image](https://github.com/user-attachments/assets/d8c3ad79-8422-4bc4-ae50-707e0795c96a)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

