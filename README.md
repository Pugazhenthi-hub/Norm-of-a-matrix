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
	4.End the program.
## Program:
```
# Register No:212224240120
# Developed By:Pugazhenthi.S
# 1-Norm of a Matrix
'''Program to find 1-norm of a matrix.
Developed by:Pugazhenthi.S
RegisterNumber: 212224240120
'''
import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm1=np.linalg.norm(arr,1)
print("{:.2f}".format(norm1))
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Pugazhenthi.S
RegisterNumber: 212224240120
'''
import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm2=np.linalg.norm(arr,2)
print("{:.2f}".format(norm2))

# Infinity Norm of a Matrix
'''
Program to find Infinity norm of a matrix.
Developed by: Pugazhenthi.S
RegisterNumber: 212224240120
'''
import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm_infinity=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm_infinity))
```
## Output:
### 1-Norm of a Matrix
![alt text](linalg07.A.png)

### 2-Norm of a Matrix

![alt text](linalg07.B.png)
### Infinity Norm of a Matrix
![alt text](linalg07.C.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
