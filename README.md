# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:MOHAMED SULTHAN A 
RegisterNumber: 23004839
*/
```
from scipy.linalg import lu
import numpy as np
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
Developed by:MOHAMED SULTHAN A 
RegisterNumber: 23004839
*/
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
## Output:
![Screenshot 2023-12-27 205104](https://github.com/Sulthan06042007/LU-Decomposition/assets/144980103/91fd3d8c-9023-4923-82df-42949f40901f)
![Screenshot 2023-12-27 205936](https://github.com/Sulthan06042007/LU-Decomposition/assets/144980103/c1a4a2f0-efac-4779-bf2d-525aaa9ce259)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

