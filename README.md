# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:

# 1-Norm of a Matrix
```
'''
Prgram to find 1- norm of a matrix
Developed By : SAI SANJIV R
Register Number: 212223230179
'''

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat , 1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: SAI SANJIV R
RegisterNumber: 212223230179
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```
'''
Program to find Infinity-norm of a matrix.
Developed By : SAI SANJIV R
Register Number: 212223230179
'''

import numpy as np
mat = np.array(eval(input()))
ans =  np.linalg.norm(mat , np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-05 170822](https://github.com/SaiSanjiv/Norm-of-a-matrix/assets/151772975/f5f5f08e-40d1-41e2-bbed-4d9c2640efa2)



### 2-Norm of a Matrix

![Screenshot 2024-05-05 170835](https://github.com/SaiSanjiv/Norm-of-a-matrix/assets/151772975/2eedb4c7-62e7-4fe3-baef-44e66784ba0f)


### Infinity Norm of a Matrix

![Screenshot 2024-05-05 170853](https://github.com/SaiSanjiv/Norm-of-a-matrix/assets/151772975/18579d47-2e91-4b5a-970a-4bcd0ef84963)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
