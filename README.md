# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define a function named circulate with no parameters
### Step 2: 
Assign the value of int(input()) to variable named 1
### Step 3: 
Assign the value of int(input()) to a variable named n
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print a message that saays" After circulating the vaues are:" followed by the value of 1
### Step 6: 
## Program:
```
#program to circulate N values.
#Developed by:ILAIYADEEPAN . K
#Reference Number:23013535
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![output](/circulate.png)

## Result:
