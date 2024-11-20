### Date : 
# Ex-7 : Norm of a matrix
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
## Name:AANKARSH
## Reg no:24013602
### 1-Norm of a Matrix
```
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
```
### 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
```
### Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![](https://github.com/user-attachments/assets/98392af7-1fea-4776-9c1f-57b592def31e)


### 2-Norm of a Matrix

![](https://github.com/user-attachments/assets/619d22fb-6154-4efb-93e3-35a32cca3db1)

### 3-Infinity Norm of a Matrix
![](https://github.com/user-attachments/assets/cb27045d-6772-4cee-9c74-16ee861435f8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
.
