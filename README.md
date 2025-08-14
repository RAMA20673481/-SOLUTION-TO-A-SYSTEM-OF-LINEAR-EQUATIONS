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
````
#Program to find the solution for the given linear equations.
#Developed by: G.Ramanujam
#RegisterNumber:212224240129
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)
````
## Output:

<img width="941" height="272" alt="Screenshot 2025-08-14 100037" src="https://github.com/user-attachments/assets/2fa08f71-a83c-4700-b42e-ad537b136475" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

