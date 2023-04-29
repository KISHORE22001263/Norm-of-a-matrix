# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:   
  - STEP1.   
 Get the input matrix using np.array()   
  - STEP2.   
 Find the 2-norm of the matrix using np.linalg.norm()
  - STEP3.   
 Print the norm of the matrix in two decimal places.
## Program:
# 1-Norm of a Matrix
```
 '''
python program to find the 1-Norm of a matrix 
Developed by:KISHORE.B
Reference No.:212222110020
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: KISHORE.B
RegisterNumber: 212222110020
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Infinity Norm of a Matrix
```
'''
program to find the Infinity of a matrix and display the result in two decimal places.
Name:KISHORE.B
REGISTER NO.:212222110020
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-04-29 181116](https://user-images.githubusercontent.com/121484538/235303330-b57905c9-42fc-401f-a66d-b964b8c49b90.png)
### 2-Norm of a Matrix
![Screenshot 2023-04-29 181139](https://user-images.githubusercontent.com/121484538/235303359-0772e5c9-8018-42ca-945e-d699684ed6ff.png)
### Infinity Norm of a Matrix
![Screenshot 2023-04-29 181218](https://user-images.githubusercontent.com/121484538/235303370-982b1b93-cad9-48b6-9892-f18a6a542a0d.png)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
