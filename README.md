# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### 2-norm
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm() by passing 2 in second parameter
	3. Print the norm of the matrix in two decimal places.
### 1-norm
    1. Get the input matrix using np.array()
	2.Find the 1-norm of the matrix using np.linalg.norm() by passing 1 in second parameter
	3. Print the norm of the matrix in two decimal places.
### Infinity Norm
    1. Get the input matrix using np.array()
	2. Find the infinity norm of the matrix using np.linalg.norm() by passing np.inf in second parameter
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# 1-Norm of a Matrix
import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np

# Type your code here

matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix

import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,np.inf)
print(norm)



```
## Output:
### 1-Norm of a Matrix
<img width="1278" height="845" alt="image" src="https://github.com/user-attachments/assets/bfeb7b4b-7836-4420-9935-fd340c2edb6e" />



### 2-Norm of a Matrix
<img width="1281" height="921" alt="image" src="https://github.com/user-attachments/assets/348eb7b9-3197-4173-bf3a-89b127d81a2a" />



### Infinity Norm of a Matrix
<img width="1269" height="811" alt="image" src="https://github.com/user-attachments/assets/88d4a016-9d15-4e00-95cd-e7f233332251" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
