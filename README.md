# Norm of a matrix

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
3.	
## Algorithm:
1. Get the input matrix using np.array()
2.  Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

## Program:
```
# Register No: 212224230178
# Developed By: VD Natchathira
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
<img width="815" height="206" alt="Screenshot 2025-10-16 104030" src="https://github.com/user-attachments/assets/0a1f9f32-551d-4dfa-8e04-abeb143cd061" />

### 2-Norm of a Matrix
<img width="810" height="244" alt="Screenshot 2025-10-16 104247" src="https://github.com/user-attachments/assets/0a4ffc46-2006-4a87-8ac7-dad3ef90e275" />

### Infinity Norm of a Matrix
<img width="810" height="204" alt="Screenshot 2025-10-16 104255" src="https://github.com/user-attachments/assets/815c7b56-ca51-49bb-bd05-2f88ca728fe5" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
