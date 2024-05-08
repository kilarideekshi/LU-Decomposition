# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the Numpy library using the statement import numpy as np.
2. Define the given matrix A
3. Compute the LU Decomposition using np.linalg.inv()
4. print and end the program

## Program:
```
(i) To find the L and U matrix

#Use LU Decomposition to find L and U matrix.INPUT:[[3,2,7],[2,3,1],[3,4,1]]
'''program to find L and U matrix using LU decompostition.
Develeped by : Divya.A
RegisterNumber:2305002007
'''
#To print L and U matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)  
    
(ii) To find the LU Decomposition of a matrix

Use LU Decomposition to solve a matrix.INPUT:[[3,2,7],[2,3,1],[3,4,1]]   [4,5,7]
'''program to find L and U matrix using LU decompostition.
Develeped by : Divya.A
RegisterNumber:2305002007
'''
#To print X matrix(solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/kilarideekshi/LU-Decomposition/assets/155507099/71436cb3-d8bc-4c67-b74e-288feb8c100d)
![image](https://github.com/kilarideekshi/LU-Decomposition/assets/155507099/d061cafc-d929-4b1e-a0f0-0768eff2ae66)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

