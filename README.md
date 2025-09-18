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
# Register No:212224240181
# Developed By:VEDHANTH H
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: VEDHANTH H
RegisterNumber: 212224240181

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2) 
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<br><img width="1391" height="965" alt="Screenshot 2025-09-18 091747" src="https://github.com/user-attachments/assets/4912733c-3159-47f3-9dc9-459b8445b16c" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1414" height="978" alt="Screenshot 2025-09-18 091807" src="https://github.com/user-attachments/assets/9a70cb89-adc8-4b0a-9c52-7f298758b0fb" />

### Infinity Norm of a Matrix
<br>
<br><img width="1420" height="938" alt="Screenshot 2025-09-18 091821" src="https://github.com/user-attachments/assets/c9882de0-f781-4c6c-a623-759649829bf9" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
