# Numpy Arrays And Its Functions

## AIM:
To Create a numpy program using the absolute builtin function of numpy to print absolute value of given numpy array.

## ALGORITHM:
1. Start

2. Import the NumPy library as np

3. Prompt the user to enter a list of numbers

    Input format should be Python-style list (e.g., [1, -2, 3, -4])
    
    Use eval() to interpret the input as a list

4. Convert the list to a NumPy array using np.array()

    Store the result in variable a

5. Calculate the absolute value of each element in the array using abs(a)

    Store the result in variable b

6. Print the resulting array b

7. End.

## PROGRAM:
```
Developed by: Naveenkumar M
Reg No: 212224230182

import numpy as np
a=np.array(eval(input()))
b=abs(a)
print(b)

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/b28f6230-59b9-429c-b542-d2f8cc01c1b7)

## RESULT:
The expected output is successfully executed.
