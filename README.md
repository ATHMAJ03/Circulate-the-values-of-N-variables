# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a function called Circulate


### Step 2: 
Create two variables and ask the values


### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
After, give the print statement


### Step 6: 
End the program


## Program:
```
#Program to circulate N values.
#Developed by: ATHMAJ VENUGOPAL
#RegisterNumber:22007603
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![Output](/Screenshot%20from%202022-12-25%2023-25-03.png)

## Result:
Thus the circulation of n variables are successfully executed.
