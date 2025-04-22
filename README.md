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
# Register No:212224240142
# Developed By:Sanchita Sandeep
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: Sanchita Sandeep
RegisterNumber: 212224240142
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Sanchita Sandeep
RegisterNumber: 212224240142
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix
'''
Program to find Infinity of a matrix.
Developed by: Sanchita Sandeep
RegisterNumber: 212224240142
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))






```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-22 111517](https://github.com/user-attachments/assets/d57a6a2a-1a2d-4371-8c7f-437909ce3f1b)


### 2-Norm of a Matrix
![Screenshot 2025-04-22 111638](https://github.com/user-attachments/assets/243f474d-4b26-4f74-8941-5ab148edd5e4)


### Infinity Norm of a Matrix
![Screenshot 2025-04-22 111805](https://github.com/user-attachments/assets/1ed6252c-224d-42cd-ac25-0248671baf31)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
