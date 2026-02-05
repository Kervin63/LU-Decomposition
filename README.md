# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Kervin.S
RegisterNumber: 212225220051

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Kervin.S
RegisterNumber: 212225220051

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
*/
```

## Output:
![lu decomposition]()
<img width="1920" height="1080" alt="Screenshot 2026-02-05 142003" src="https://github.com/user-attachments/assets/263549c3-5313-4096-837c-abd1c0bbf8bb" />
<img width="1920" height="1080" alt="Screenshot 2026-02-05 142016" src="https://github.com/user-attachments/assets/9bec7cc4-860d-4476-a5c1-b4dd18fac667" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

