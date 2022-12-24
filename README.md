# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Assign the function for the code
### Step 2: 
Get the value from the user (n)
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the values after rotating

## Program:
```py
#Program to circulate N values.
#Developed by: shalini
#RegisterNumber: 22009257
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)



```

## Output:
![output](/2.png)

## Result:
Thus the swapping of two values are successfully executed
