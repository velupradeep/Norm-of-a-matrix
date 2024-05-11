# NAME:PRADEEP V
# REG NO:212223240119
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
1.
```
'''
program to find 1-norm of a matrix.
Developed by:PRADEEP V
Register Number:23013543
'''
import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,1)
norm="{:.2f}" .format(sol)
print(norm)
```
2.
```
'''
Program to find 2-norm of a matrix.
Developed by: PRADEEP V
RegisterNumber: 23013543
'''
import numpy as np
a=([[1,2],[3,4],[1,7]])
b=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,2)
norm="{:.2f}".format(sol)
print(norm)
```
3.
```
'''
program to find 2-norm of a matrix.
Developed by:PRADEEP V
Register Number:23013543
'''
import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(sol)
print(norm)
```


## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-24 104812](https://github.com/velupradeep/Norm-of-a-matrix/assets/150329341/6a123633-c1d9-4cf8-b0f5-ddb3f11d9857)


### 2-Norm of a Matrix
![Screenshot 2023-12-24 104843](https://github.com/velupradeep/Norm-of-a-matrix/assets/150329341/8bd1c9d4-b073-43e9-8bcb-f467a2d4426e)


### Infinity Norm of a Matrix
![Screenshot 2023-12-24 104917](https://github.com/velupradeep/Norm-of-a-matrix/assets/150329341/7d920120-f036-4d86-ac5a-4f05286d79d8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
