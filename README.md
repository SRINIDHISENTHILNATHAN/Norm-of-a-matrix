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
# Register No: SRINIDHI SENTHIL
# Developed By:22001408
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by:SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
import numpy as np
array=np.array(eval(input()))
n=np.linalg.norm(array,1)
print("{:.2f}".format(n))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
import numpy as np
array=np.array(eval(input()))
n=np.linalg.norm(array,2)
print("{:.2f}".format(n))




# Infinity Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by:SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)






```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/121373170/214830393-def76dab-c643-4d34-b18e-b6bc13ad1b30.png)

### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/121373170/214830457-9facde64-8bac-45b4-8ab9-7417fbfa20c7.png)

### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/121373170/214830564-3afc1dc3-7e55-4bd5-9499-14339633659e.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
