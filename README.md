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
```
Python
# Register No:24900219
# Developed By:Arun s
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
![Screenshot 2024-12-05 194531](https://github.com/user-attachments/assets/b3cb8533-cd02-40d5-a1c4-2117ae527586)


### 2-Norm of a Matrix
![Screenshot 2024-12-05 194559](https://github.com/user-attachments/assets/9a3befb1-006f-494f-8cac-eb595249e431)


### Infinity Norm of a Matrix
![Screenshot 2024-12-05 194659](https://github.com/user-attachments/assets/f79ff855-58e3-4f5d-9947-18b0b4210041)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
