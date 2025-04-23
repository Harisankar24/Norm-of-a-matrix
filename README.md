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
 # Register No:212224240051
 # Developed By:Harisankar.S
 # 1-Norm of a Matrix
 import numpy as np
 mat=np.array(eval(input()))
 ans=np.linalg.norm(mat,1)
 norm_of_matrix="{:.2f}".format(ans)
 print(norm_of_matrix)



# 2-Norm of a Matrix

 '''
 Program to find 2-norm of a matrix.
 Developed by:Harisankar.S
 RegisterNumber:212224240051
 '''
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
![Screenshot 2025-04-21 132910](https://github.com/user-attachments/assets/d12a75b5-c653-4d38-b844-9a6a15891fb9)


### 2-Norm of a Matrix

![Screenshot 2025-04-21 132939](https://github.com/user-attachments/assets/73e98c1f-5da5-4ce8-b4c8-29aa4c72b743)

### Infinity Norm of a Matrix
![Screenshot 2025-04-21 133010](https://github.com/user-attachments/assets/88853691-5462-4ce2-847a-9de0f1aea304)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
