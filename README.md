# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Take input from the user.

### Step 2:

Use functions and pass parameters.

### Step 3:

Get the value from the user for the number of rotation.

### Step 4:

Using the slicing concept rotate the list.

### Step 5:

print circulated values.

### Step 6:

End the program.

## PROGRAM:
```
#Program to circulate N values.
#Developed by: N.R.NAVEEN RAJA
#RegisterNumber: 212222230093
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![Circulate](/circulate.png)

## Result:
Thus the circulate of n variables using function concept are successfully executed