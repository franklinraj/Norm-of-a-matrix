# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
2.   2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 23001518
# Developed By: FRANKLIN RAJ G
# 1-Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np

# Type your code here
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-28 203354](https://github.com/franklinraj/Norm-of-a-matrix/assets/148993740/e3e08fff-113a-4adb-896d-f1be2b3c3801)


### 2-Norm of a Matrix
![Screenshot 2023-12-28 203221](https://github.com/franklinraj/Norm-of-a-matrix/assets/148993740/ee5a49cf-760d-4835-a75c-98c49828f134)


### Infinity Norm of a Matrix
![Screenshot 2023-12-28 203238](https://github.com/franklinraj/Norm-of-a-matrix/assets/148993740/6b9e57dc-5446-4f10-a19f-c82212642d28)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
