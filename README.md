# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. get input from user and print L and U matrix by 'print'
3. define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as 'X' include the package in the variable
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
/*
Program to find the L and U matrix.
Developed by: MOHAMED SULTHAN A
RegisterNumber: 23004839
*/
```
(ii) To find the LU Decomposition of a matrix
```
# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MOHAMED SULTHAN A
RegisterNumber: 23004839
*/

```

## Output:
![image](https://github.com/Sulthan06042007/LU-Decomposition/assets/144980103/781ba78b-a632-44c0-b61c-d0b2136dd78e)
![Screenshot 2023-12-27 205936](https://github.com/Sulthan06042007/LU-Decomposition/assets/144980103/58b81b8b-f9da-41cf-afc0-2ffb82775dcb)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

