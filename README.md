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
#Developed by:Boopathy S
#RegisterNumber:2305003002
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
Solution=np.linalg.solve(A,B) 
print("The solution for given matrix is",Solution)

## Output:
![Screenshot 2024-04-04 103520](https://github.com/BOOPATHYS0660/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155909381/a91d40d6-5241-40f1-a286-0d7971af12b6)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

