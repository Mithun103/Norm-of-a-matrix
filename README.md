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
# Register No:22008364
# Developed By:MITHUN ms
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)
```

# 2-Norm of a Matrix
```
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)
```

# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)
```
## Output:
### 1-Norm of a Matrix
<br>
<br>![1n](https://user-images.githubusercontent.com/118344695/215438201-f9388369-f080-4171-97a9-592154320c6e.png)


<br>

### 2-Norm of a Matrix
<br>
<br>![2n](https://user-images.githubusercontent.com/118344695/215438253-c38ca661-5988-4a34-b7ed-3f72983e5de0.png)

<br>

### Infinity Norm of a Matrix
<br>![3n](https://user-images.githubusercontent.com/118344695/215438311-39f64b83-487a-419e-86bb-d14c03a4e0ce.png)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
