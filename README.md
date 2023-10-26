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
Using concatination operation display in the entire rotated list
### Step 6: 
stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Arun Kumar B
#RegisterNumber:23004514
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![Screenshot from 2023-10-17 14-11-03](https://github.com/Arun2005-create/Circulate-the-values-of-N-variables/assets/138849356/a2871ef2-9ab9-432b-b802-95520c97ffde)


## Result:
Thus the python program for Circulate the values of a variables is executed successfully
