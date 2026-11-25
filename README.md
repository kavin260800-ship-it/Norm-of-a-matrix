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
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
print("%.2f"% np.linalg.norm(mat,1))

```




# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Abinaya P
RegisterNumber: 212225230003
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
print("%.2f" %np.linalg.norm(mat,2))

# Type your code here

```



# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat =np.array(eval(input()))
print("%.2f"% np.linalg.norm(mat,np.inf))




```
## Output:
 <img width="467" height="216" alt="Screenshot 2026-11-25 215752" src="https://github.com/user-attachments/assets/92767903-1e2d-4e48-af3c-95f17de91989" />
 <img width="787" height="205" alt="Screenshot 2026-11-25 215826" src="https://github.com/user-attachments/assets/f83278d9-7c88-425d-bab7-a0aefe439f72" />
 <img width="445" height="300" alt="Screenshot 2026-11-25 215833" src="https://github.com/user-attachments/assets/ecd74517-7687-455b-8911-47033d8865e9" />
 <img width="560" height="227" alt="Screenshot 2026-11-25 215850" src="https://github.com/user-attachments/assets/38cb8f6e-0cec-461d-b1ca-65a0dbeb7806" />
<img width="453" height="315" alt="Screenshot 2026-11-25 215856" src="https://github.com/user-attachments/assets/ca5f80c4-1196-4fd7-aee5-06a884b0e54b" />
<img width="587" height="185" alt="Screenshot 2026-11-25 215901" src="https://github.com/user-attachments/assets/f2f318d5-1393-4ff6-afe0-7d6fcfc316ce" />






## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
