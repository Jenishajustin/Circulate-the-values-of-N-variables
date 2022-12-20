# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the list of values from the user.
### Step 2: 
Get the value from the user for the number of rotation.
### Step 3: 
Declare a function starting with a keyword 'def'.
### Step 4: 
Within the function print the output statement.
### Step 5: 
Using the slicing concept rotate the list.
### Step 6: 
Display the output.
## Program:
```python
#Program to circulate N values.
#Developed by: JENISHA.J
#RegisterNumber: 22002972
list=eval(input())
n=int(input())
def circulate():
    print("After circulating the values are: {}".format(list[n:]+list[:n]))
```
## Output:

![MODEL](circulate-n-variables.png)
## Result:
Thus circulating the values of N variables is executed successfully.
