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
```Python
# Register No:23003821
# Developed By: SUBASH R
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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
![image](https://github.com/rsubash17/Norm-of-a-matrix/assets/147139828/fd613a89-66b6-47b7-a6be-62c735bce317)

### 2-Norm of a Matrix
![image](https://github.com/rsubash17/Norm-of-a-matrix/assets/147139828/94905c1e-3c16-410e-80db-2ddff732c368)

### Infinity Norm of a Matrix
![image](https://github.com/rsubash17/Norm-of-a-matrix/assets/147139828/4ee53207-bf00-432a-92cf-d2ec0ee41352)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
