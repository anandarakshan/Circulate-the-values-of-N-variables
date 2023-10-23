# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using concatenation operation display the entire rotated list
### Step 6: 
Stop the program

## Program:
```
#Program to circulate N values.
#Developed by: Ananda Rakshan K V
#RegisterNumber:23001531
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![python_2](https://github.com/anandarakshan/Circulate-the-values-of-N-variables/assets/139217934/c4484e01-379f-4f18-bfcb-a603b8374e18)


## Result:
Thus the python program for Circulate the values of n variables is executed successfully
