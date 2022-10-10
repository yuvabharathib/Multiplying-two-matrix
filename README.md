# Multiplying-two-matrix

## AIM:
To multiply two arrays

## ALGORITHM:

### Step 1:
import num as np.
### Step 2:
create two empty lists.
### Step 3:
Get input from user.
### Step 4:
Create a nested for loop and append the values to the created lists.
### Step 5:
Create two arrays.
### Step 6:
Multiply the two arrays.
### Step 7
Give print statement.

## PROGRAM:
```python
#Developed by:yuvabharathi.b
#Registration no:22002787

import numpy as np
n=int(input())
l1,l2=[],[]
for i in range(n):
    l1.append(int(input()))
for i in range (n):
    l2.append(int(input()))
array1=np.array(l1)
array2=np.array(l2)
product=array1*array2
print("Product of two arrays is:",product)
```

## OUTPUT:
![multi](https://user-images.githubusercontent.com/113497340/194228425-3a069b52-1d80-4ab6-8094-86358e5b7121.png)


## RESULT:
Hence the program is runned successfully.
