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
# Register No:212224230307
# Developed By:vutukuri sai kumar Reddy
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by:vutukuri sai kumar Reddy
RegisterNumber: 212224230307
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:vutukuri sai kumar Reddy
RegisterNumber: 212224230307
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))




# Infinity Norm of a Matrix

'''
Program to find Infinity-norm of a matrix.
Developed by:vutukuri sai kumar Reddy
RegisterNumber: 212224230307
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))



```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2025-05-11 094354](https://github.com/user-attachments/assets/07085a08-e433-433c-92ad-bb04e41dd988)

<br>
<br>

### 2-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/ea0c95f2-08f3-48ef-96ac-2a6a5ab8abf7)

<br>
<br>

### Infinity Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/13f63283-7f98-43cd-8ab4-62ee29d3d738)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
