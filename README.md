# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm:  
### Step 1: 
Get the two values from the user
### Step 2: 
Assign the values of second variable to temporary variable 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```

#Program to circulate N values.
#Developed by: ABDUL KALAAM K M
#RegisterNumber:23005114
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)

```
## Output:
![Screenshot 2023-12-27 143717](https://github.com/dfghytr/Circulate-the-values-of-N-variables/assets/138970628/5d7f049a-2af9-4fd7-b68f-2d5da12dcde4)

## Result:
completed successfully.
