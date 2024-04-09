# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define a function as circulate
### Step 2: 
get the valuse from the user for the list using eval()
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the output usring print statement

## Program:
```
def circulate():
    a=eval(input())
    n=eval(input())
    b=a[n:]+a[:n]
    print("After circulating the values are:",b)
```
## Output:
![Screenshot 2024-04-09 133028](https://github.com/Keerthika23013559/Circulate-the-values-of-N-variables/assets/162658262/9517228a-be07-40bc-ade3-34e67636ac93)

## Result:
thus the program is successfully executed
