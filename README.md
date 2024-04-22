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

```
Developed By: M THEJESWARAN
Reg no:212223240168

import numpy as np

A=np.array([[1,3],[2,5]])
B=np.array([5,-3])

get_ans=np.linalg.solve(A,B)

print(get_ans)

```

## Output:
![Screenshot (1)](https://github.com/TEJA190905/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/167788543/ba9797c1-a2f1-4a6c-9b78-cebdb857837a)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

