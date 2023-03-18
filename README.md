# Circulate-the-values-of-N-variables

## Aim:

To write a python program to circulate the n variables using function concept

## Equipment’s required:

PC
Anaconda - Python 3.7

## Algorithm: 

### Step 1: 

Get n variable from the user

### Step 2: 
get the input

### Step 3: 
Get the value from the user for the number of rotation

### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the values it would be interchanged

### Step 6: 

End the program

## Program:
```python
#Program to circulate N values.
#Developed by:Renuga.S 
#RegisterNumber:212222230118
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:



![circulate](https://user-images.githubusercontent.com/119292258/226090075-ebdea0f3-eb3b-4b55-a883-617fc3815450.png)



## Result:
Thus the circulation of n variable successfully executed.
