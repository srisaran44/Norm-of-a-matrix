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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br><img width="1217" height="258" alt="image" src="https://github.com/user-attachments/assets/ae03e0b0-9c0f-4195-8ccb-ac398a642013" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1069" height="298" alt="image" src="https://github.com/user-attachments/assets/14981d03-a247-43ff-ae6a-216411f920ac" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<br>
<br><img width="1078" height="260" alt="image" src="https://github.com/user-attachments/assets/66d484dd-f2ac-4cf4-9e94-86f0ae40fd78" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
