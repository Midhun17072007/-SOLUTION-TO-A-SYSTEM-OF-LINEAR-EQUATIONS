# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
~~~
#Program to find the solution for the given linear equations.
#Developed by: MIDHUN S
#RegisterNumber:212224230158

import numpy as np
a = np.array([[1,-3],[3,1]])
b = np.array([0,10])
c = np.linalg.solve(a,b)
print(c)
~~~
## Output:
![Screenshot 2025-04-26 104420](https://github.com/user-attachments/assets/3a6bdf3c-5eac-4b0d-a429-c4dc495ac54b)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

