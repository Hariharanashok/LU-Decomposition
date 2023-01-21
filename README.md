# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use built-in functions for calculation.
2.Import lu package, lu_factor and lu_solve from scipy.linalg module.
3.Using lu_factor() and lu_solve(), we can find the solutions.
4.End the program. 

## Program:
(i) To find the L and U matrix
```python
#Program to find the L and U matrix.
#Developed by: HARIHARAN A
#RegisterNumber: 22001891

import numpy as np        #from numpy import array
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```python
#Program to find the LU Decomposition of a matrix.
#Developed by: HARIHARAN A
#RegisterNumber: 22001891

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

```

## Output:
![image](https://user-images.githubusercontent.com/120353431/213847067-d1c62847-6c49-4391-810a-f6b99ee64e5c.png)
![image](https://user-images.githubusercontent.com/120353431/213847108-08999883-90a0-4d60-8f66-adfe5e2a0e82.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

