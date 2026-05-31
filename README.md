# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: Start the program
### Step 2: Initialise the values in the list
### Step 3: Get the value from the user for the number of rotation
### Step 4: Using the slicing concept rotate the list
### Step 5: slice the number of values required
### Step 6: Then paste it at the back to circulate
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print(f"After circulating the values are: {l}")
```
## Output:
<img width="1300" height="996" alt="image" src="https://github.com/user-attachments/assets/4d49742a-6960-4ca9-b18a-60e993c814f8" />


## Result:
Output executed successfully
