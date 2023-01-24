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
# Register No:22009150
# Developed By:Archana.k

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
![Screenshot 2023-01-24 200813](https://user-images.githubusercontent.com/118708624/214325544-bcc5d7c0-ac5c-4664-8b75-431586e28873.png)


### 2-Norm of a Matrix
![Screenshot 2023-01-24 201839](https://user-images.githubusercontent.com/118708624/214326128-fcfd0eb5-f3d0-47bf-a382-337d2f6d3309.png)


### Infinity Norm of a Matrix
![Screenshot 2023-01-24 202041](https://user-images.githubusercontent.com/118708624/214326620-d88da010-c968-4dc3-9d46-ff61f8add594.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
